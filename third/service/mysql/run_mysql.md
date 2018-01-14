# 安装mysql client
```
brew install mysql
```
# 获取mysql镜像
```
sudo docker pull mysql
```
# 查看镜像
```
sudo docker images
```
# 启动容器

bash run.docker.sh
# 查看容器
docker ps

# 测试容器

mysql -h 192.168.0.104 -P 3306 -u root -p

# 停止容器
docker stop firt-mysql
