# Centos_Docker_Install
1.移除旧版本

sudo yum remove docker \
                  docker-client \
                  docker-client-latest \
                  docker-common \
                  docker-latest \
                  docker-latest-logrotate \
                  docker-logrotate \
                  docker-engine

2、安装docker

yum -y install docker

3、启动docker

systemctl start docker.service

4、设置docker开机启动

systemctl enable docker.service
