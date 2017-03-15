# Apache
apache配置中的一点小错误

error discription : Windows不能在本地计算机启动Apache2.2  。。。 并参考特定服务错误代码1
此时，是 httpd.conf 文件出错，出错原因之一：
搜索 "ServerAdmin "改为 "#ServerAdmin "， 其中这里设置的是一个邮箱，邮箱设置可能出错了
