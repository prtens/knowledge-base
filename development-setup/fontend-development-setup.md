前端开发配置
=========

前端采用webpack打包，以下配置使用与Linux或Mac

## 安装node和cnpm
    
```
curl -O https://mirrors.ustc.edu.cn/node/v6.9.5/node-v6.9.5-linux-x64.tar.xz
xz -d node-v6.9.5-linux-x64.tar.xz
tar xvf node-v6.9.5-linux-x64.tar
rm -rf node-v6.9.5-linux-x64.tar
mv node-v6.9.5-linux-x64 /usr/local/node
ln -s /usr/local/node/bin/node /usr/bin/
ln -s /usr/local/node/bin/npm /usr/bin/
alias cnpm="npm --registry=https://registry.npm.taobao.org \
--cache=$HOME/.npm/.cache/cnpm \
--disturl=https://npm.taobao.org/mirrors/node \
--userconfig=$HOME/.cnpmrc"
```

## 依赖安装

为避免npm因版本问题出现一些未知错误，统一使用cnpm来安装依赖

```
# 添加淘宝镜像(安装4.4.0以上版本，只需执行一次)
npm install -g cnpm --registry=https://registry.npm.taobao.org
# 安装依赖
cnpm install
```

## 开发模式

```
npm run dev
npm run dev port:3034 #改变端口
```

```
#此命令默认会绑定到3030端口，但不会生成真实文件，但可以通过http://127.0.0.1:3030/static 浏览到文件目录
```

## 最终编译

```
#会生成实体文件，本项目会生成到web/static/
npm run compile
npm run compile:debug  #不压缩
```