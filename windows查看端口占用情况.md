# netstat命令

+ **-a**，显示所有活动的TCP连接以及计算机监听的TCP和UDP端口；
+ **-e**，显示以太网发送和接收的字节数、数据包数等；
+ **-n**，只以数字形式显示所有活动的TCP连接的地址和端口号；
+ **-o**，显示活动的TCP连接并包括每个连接的进程ID（PID）；
+ **-s**，按协议显示各种连接的统计信息，包括端口号；

# 查看本地端口占用情况

`netstat -ano`

![查看端口占用情况](http://www.xitongzhijia.net/uploads/allimg/190513/66-1Z513163111-52-water.jpg "查看端口占用情况")



在任务管理器中，根据PID就可以查看对应的进程信息。

![在任务管理器中查看进程信息](http://www.xitongzhijia.net/uploads/allimg/190513/66-1Z513163110-water.jpg "在任务管理器中查看进程信息")

