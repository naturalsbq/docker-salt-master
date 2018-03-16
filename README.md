# docker-salt-master
基于ubuntu 14.04 安装 salt-master 2016.11

安装步骤参考salt官方网站

docker run --name salt-master 
-v /etc/salt 
-p 4505:4505 -p 4506:4506 
-d sunbingqian/salt-master:2016.11
