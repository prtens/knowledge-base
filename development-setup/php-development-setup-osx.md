# MAC环境配置PHP开发环境

## 先更新brew

```bash
brew update
```

## 安装xcode工具

```bash
xcode-select --install
```

## 安装nginx

```bash
brew install nginx
```

## 配置nginx

```bash
lineNum=`sed -n -e '/sendfile/=' /etc/nginx/nginx.conf`; sed -i $((lineNum+1))'i client_max_body_size 1024M;' /usr/local/etc/nginx/nginx.conf
```

## nginx host配置路径

/usr/local/etc/nginx/servers

## 重新配置nginx

```bash
sudo nginx -s reload
```

## 安装mysql

```bash
brew install mysql
```

## 启动mysql

```bash
sudo mysql.server start
```

## 修改mysql目录用户组

```bash
sudo chown -R _mysql:_mysql /usr/local/var/mysql
```

## 再次启动

```bash
sudo mysql.server start
```

## 安装php71和php-fpm

```bash
brew tap homebrew/dupes

brew tap josegonzalez/homebrew-php

# (如果tap错了，可以brew untap xxx删除)

brew install php71 --with-debug --with-mysql --with-pear --with-imap



```

## 配置php

```bash
vim /usr/local/etc/php/7.1/php.ini

# 修改以下配置(vim搜索方法：向下搜索命令行模式输入/post_max，向上搜索?post_max，下一项n，上一项N)

post_max_size ＝ 1024M

memory_limit ＝ 1024M

upload_max_filesize ＝ 1024M
```

## 配置php-fpm

```bash
vim /usr/local/etc/php/7.1/php-fpm.d/www.conf

# 查找
listen = 127.0.0.1:9000 
#替换为
listen = /var/run/php71-fpm.sock

#找到以下三句，删除前面的分号
;listen.owner = _www
;listen.group = _www
;listen.mode = 0660

#创建软连接启动php-fpm
ln -s /usr/local/opt/php71/sbin/php71-fpm /usr/local/bin/

```

## 启动

```bash
sudo php71-fpm start
```







