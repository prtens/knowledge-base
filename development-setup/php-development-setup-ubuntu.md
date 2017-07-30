开发环境配置
=============

注意：Windows下开发者，推荐使用预装了以下环境的VirtualBox虚拟机，请移步[VirtualBox配置](virtual-box-setup.md)，可以跳过“安装开发的初始环境”步骤。

建议在Linux下做开发，以下的配置基于Ubuntu14.04。

以下配置中myproject表示项目英文名称，请按照实际修改。

## 初始化开发环境

### 安装git

```
apt-get install -y git
```

### 安装php71 

* 安装

```
apt-get install -y software-properties-common && DEBIAN_FRONTEND=noninteractive add-apt-repository ppa:ondrej/php && apt-get update
apt-get install -y php7.1 php7.1-cli php7.1-curl php7.1-fpm php7.1-intl php7.1-mcrypt php7.1-mysqlnd php7.1-gd php7.1-dom
```

* 配置fpm

```
sed -i "s/;*listen.owner\s*=\s*www-data/listen.owner = www-data/g" /etc/php/7.1/fpm/pool.d/www.conf
sed -i "s/;*listen.group\s*=\s*www-data/listen.group = www-data/g" /etc/php/7.1/fpm/pool.d/www.conf
sed -i "s/;*listen.mode\s*=\s*0660/listen.mode = 0660/g" /etc/php/7.1/fpm/pool.d/www.conf
sed -i "s/;*listen\s*=\s*\S*/listen = 127.0.0.1:9000/g" /etc/php/7.1/fpm/pool.d/www.conf
```
* 配置php

```
sed -i "s/;*post_max_size\s*=\s*\w*/post_max_size = 1024M/g" /etc/php/7.1/fpm/php.ini
sed -i "s/;*memory_limit\s*=\s*\w*/memory_limit = 1024M/g" /etc/php/7.1/fpm/php.ini
sed -i "s/;*upload_max_filesize\s*=\s*\w*/upload_max_filesize = 1024M/g" /etc/php/7.1/fpm/php.ini
sed -i "s/;*display_errors\s*=\s*\w*/display_errors = On/g" /etc/php/7.1/fpm/php.ini
```
* 重启php-fpm

```
/etc/init.d/php7.1-fpm restart
```

### 安装nginx

```
apt-get install -y nginx
```
      
### 安装mysql

* 注意：安装过程中会提示输入密码，本地开发推荐密码设置成root

```
apt-get install -y mysql-server-5.6
```

* 配置mysql

```
sed -i "s/;*max_allowed_packet\s*=\s*\w*/max_allowed_packet = 1024M/g" /etc/mysql/my.cnf
```

### 进入程序目录

* 注意按照自己的实际目录来，下方的nginx配置中目录也需要按照实际修改

```
cd /var/www/myproject
```

### 创建配置文件

```
cp app/config/parameters.yml.dist app/config/parameters.yml
```

并修改配置文件中的数据库配置

### 创建数据库

* 进入MySQL命令行

````
mysql -uroot -p
````

* 在mysql命令行下，创建数据库

````
mysql> CREATE DATABASE `myproject` DEFAULT CHARACTER SET utf8 ; 
mysql> exit;
````

### 初始化程序基础数据

```
bin/phpmig migrate
app/console app:init
```

### 配置Nginx
        
* 新增一个虚拟主机，在/etc/nginx/sites-enabled/下新建一个myproject.io文件，输入以下内容

```
server {
    set $root_dir /var/www/myproject;
    
    listen 80;

    server_name myproject.io;

    root $root_dir/web;

    access_log /var/log/nginx/myproject.io.access.log;
    error_log /var/log/nginx/myproject.io.error.log;
    
    location / {
        try_files $uri /app_dev.php$is_args$args;
    }
    
    location ~ ^/(app|app_dev)\.php(/|$) {
        fastcgi_pass 127.0.0.1:9000;
        fastcgi_split_path_info ^(.+\.php)(/.*)$;
        include fastcgi_params;
        fastcgi_param  SCRIPT_FILENAME    $document_root$fastcgi_script_name;
        fastcgi_param  HTTPS              off;
        fastcgi_param HTTP_X-Sendfile-Type X-Accel-Redirect;
        fastcgi_param HTTP_X-Accel-Mapping /udisk=$root_dir/app/data/udisk;
        fastcgi_buffer_size 128k;
        fastcgi_buffers 8 128k;
    }
    
    location ~ ^/static {
        # webpack端口按照实际前端开发配置做修改
        rewrite ^(.*)$ http://127.0.0.1:3034$1 last;
    }

    location ~ ^/udisk {
        internal;
        root $root_dir/app/data/;
    }

    location ~* \.(jpg|jpeg|gif|png|ico|swf)$ {
        expires 3y;
        access_log off;
        gzip off;
    }

    location ~* \.(css|js)$ {
        access_log off;
        expires 3y;
    }

    location ~ \.php$ {
        fastcgi_pass 127.0.0.1:9000;
        fastcgi_split_path_info ^(.+\.php)(/.*)$;
        include fastcgi_params;
        fastcgi_param  SCRIPT_FILENAME    $document_root$fastcgi_script_name;
    }
}
```

### /etc/hosts里添加

```
127.0.0.1 myproject.io
```

### 浏览器打开 myproject.io

```
默认账号为：admin
密码为：kaifazhe
```

## 数据库变更脚本

### 查看所有命令

```
bin/phpmig
```

### 生成一个Migration脚本类

```
bin/phpmig generate ClassName ./migrations
```

第一个参数`ClassName`为本次Migration脚本类的类名，请根据实际情况取名，表明意图。
第二个参数`./migrations`为Migration脚本类的存放目录，请使用约定值`./migrations`。

### 运行所有为执行过的Migration脚本

```
bin/phpmig migrate
```

### 重新执行某个具体版本的Migration脚本

```
bin/phpming redo VERSION_NO
```

### 回退最后执行过的一个版本

```
bin/phpmig rollback
```

## 单元测试

### 创建测试数据库

```
mysql -uroot -proot

CREATE DATABASE `myproject-test` DEFAULT CHARACTER SET utf8;
```

### 执行所有单元测试

```
phpunit -c app/ 
```

### 执行某个单元测试

```
phpunit -c app TEST_CAST_FILEPATH
```
