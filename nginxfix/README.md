这里是nginx的自动重启脚本，我把它做成了一个服务，好像是多此一举了。
默认把整个文件夹放在/root下，里面的nginxfix.service文件则放在/etc/systemd/system下
脚本文件就一个，log文件夹则是存放脚本最后一次产生的错误日志和邮件发送的文本日志，邮件发送的地址记得改成管理员的地址
