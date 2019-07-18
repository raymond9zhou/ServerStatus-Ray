# ServerStatus-Ray
云探针、多服务器探针、云监控、多服务器云监控
基于ServerStatus-Toyo和CokeMine的魔改版本进行修改，用过去15分钟内的Load Average作为负载值（原来使用端口的连接数）

## 特性

模板来自：<https://www.hostloc.com/thread-494384-1-1.html>

## 安装方法
```
wget https://raw.githubusercontent.com/raymond9zhou/ServerStatus-Ray/master/status.sh
chmod +x status.sh
./status.sh
```
按照提示进行即可
#注意#，正常安装方式会安装caddy，如已安装了其他web服务不需要caddy的可选择不安装

## 手动安装



当然前端可以自己自定义。

## 相关开源项目 ： 
* ServerStatus-Toyo：https://github.com/ToyoDAdoubiBackup/ServerStatus-Toyo
* ServerStatus：https://github.com/BotoX/ServerStatus
* mojeda: https://github.com/mojeda 
* mojeda's ServerStatus: https://github.com/mojeda/ServerStatus
* BlueVM's project: http://www.lowendtalk.com/discussion/comment/169690#Comment_169690
