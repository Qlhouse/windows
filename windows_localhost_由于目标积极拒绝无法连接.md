# 问题背景

在尝试python socket编程的时候，首先将编写好的客户端给和服务器都部署在本地运行，并且使用同一台宿主机，客户端使用127.0.0.1，服务器端使用0.0.0.0或者127.0.0.1。    

刚开始

刚开始我端口时随意选择的，比如8080，9090， 然后一直出现报错：**由于目标积极拒绝，无法连接**。

`ping 127.0.0.1`也没有问题，这个时候，**telnet你选择的端口**，看看端口是不是开启的。

![](https://img-blog.csdnimg.cn/20200517093415513.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ0NjU0NDk4,size_16,color_FFFFFF,t_70 "telnet选择的端口")



要查看系统开放的端口，使用`netstat -an`命令。

![](https://img-blog.csdnimg.cn/20200517093714286.png?x-oss-process=image/watermark,type_ZmFuZ3poZW5naGVpdGk,shadow_10,text_aHR0cHM6Ly9ibG9nLmNzZG4ubmV0L3FxXzQ0NjU0NDk4,size_16,color_FFFFFF,t_70 "查看系统开放的端口")



那些处于listening状态的端口都是可以使用的。

