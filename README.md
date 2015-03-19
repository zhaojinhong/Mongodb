# Mongodb
#创建镜像：
#sudo docker build -t mongodb .

#启动容器，映射27017和28017端口到本地：
#sudo docker run -d -p 27017:27017 -p 28017:28017 mongodb

#通过docker logs查看admin账号和密码：
#sudo docker logs sa9



###################可以在容器启动时指定admin账号和密码###############################
#sudo docker run -d -p 27017:27017 -p 28017:28017 -e MONGODB_PASS="mypass" mongodb
#甚至设置不需要密码：
#sudo docker run  -d -p 27017:27017 -p 28017:28017 -e AUTH=no mongodb


