# Centos7-Shadowsocks-
关于shadowsocks安装后的问题记录在此

网上关于安装Shadowsocks的教程已经有很多了,按照操作就行。今天安装完后发现手机连不上。在此记录下故障：安装完后要开启防火墙相应的端口才可以: 

firewall-cmd --permanent --add-port=自己设置的端口号/tcp

firewall-cmd --reload

运行这两条命令就可以了。
