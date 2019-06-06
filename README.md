# docker-compose-wordPress
#使⽤Docker Compose编排WordPress博客

#执行下面的命令
mkdir docker-compose-wordpress
cd docker-compose-wordpress
wget https://raw.githubusercontent.com/673tong/docker-compose-wordPress/master/docker-compose.yml
docker-compose up

#安装完访问：http://ip:40010

#停止WordPress
[root@localhost ~]# docker stop 9f7c9dc13277 
#或者
[root@localhost ~]# docker-compose stop wordpress
Stopping root_wordpress_1 ... done

#启动WordPress
[root@localhost ~]# docker start 9f7c9dc13277 
#或者
[root@localhost ~]# docker-compose start wordpress
Starting wordpress ... done

mysql用户/密码：
