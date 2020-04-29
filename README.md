安装

服务端
wget https://raw.githubusercontent.com/CokeMine/ServerStatus-Hotaru/master/status.sh
bash status.sh s
脚本中有可选项，选择是安装新的 Nginx 程序或不安装而使用自己已经安装的 Nginx
如果使用自己的 Nginx 程序则需要将 /usr/local/ServerStatus/web 目录设置为网站目录即可
可以选择在使用脚本时就直接做好配置或者在 /usr/local/ServerStatus/server 中直接编辑 config.json 文件
客户端
wget https://raw.githubusercontent.com/CokeMine/ServerStatus-Hotaru/master/status.sh
bash status.sh c
可以选择在使用脚本时就直接做好配置或者在 /usr/local/ServerStatus/client 中直接编辑 status-client.py 文件
个人建议

ServerStatus-Hotaru 的图片使用有点花里胡哨，建议直接编辑 /usr/local/ServerStatus/web/css/hotaru_fix.css 这个文件，将头部背景图去掉，或者直接把 img 文件夹中的图片删除




# ServerStatus-Hotaru0
云探针、多服务器探针、云监控、多服务器云监控

基于ServerStatus-Toyo最新版本稍作修改，不太会脚本什么的，前端也垃圾。见谅

Test v0.014：图片来源：Pixiv：72725286

## 特性

模板来自：<https://www.hostloc.com/thread-494384-1-1.html>

稍作修改。

多了个Region调用国旗。所以用原来Toyo版的需要稍作修改

## 安装方法

请见：https://www.cokemine.com/serverstatus-hotaru.html

## 修改方法

配置文件：/usr/local/ServerStatus/server/config.json备份并自行添加Region

![](https://i.loli.net/2019/02/07/5c5bca12df8b0.png)

卸载ServerStatus-Toyo安装ServerStatus-Hotaru替换配置文件，重启ServerStatus

## 效果演示

![](https://i.loli.net/2019/04/05/5ca74fb05338f.png)

![](https://i.loli.net/2019/04/05/5ca74fc86db96.png)

当然前端可以自己自定义。

## 相关开源项目 ： 
* ServerStatus-Toyo：https://github.com/ToyoDAdoubiBackup/ServerStatus-Toyo
* ServerStatus：https://github.com/BotoX/ServerStatus
* mojeda: https://github.com/mojeda 
* mojeda's ServerStatus: https://github.com/mojeda/ServerStatus
* BlueVM's project: http://www.lowendtalk.com/discussion/comment/169690#Comment_169690
