1，启动双节点的服务注册中心集群

java -jar eureka-server-0.0.1-SNAPSHOT.jar --spring.profiles.active=peer1

java -jar eureka-server-0.0.1-SNAPSHOT.jar --spring.profiles.active=peer2

2，为使配置能够正常访问，在本地的hosts文件中添加对peer1和peer2的转换

    127.0.0.1 peer1

    127.0.0.1 peer2

3，访问

http://localhost:1111/ 和
http://localhost:1112/
