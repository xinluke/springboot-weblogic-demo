# springboot-weblogic-demo
## 基础说明
springboot 1.5.X版本可以直接在weblogic中成功部署
springboot 2.X 版本部署需要调整weblogic，暂时还没测试，具体可以google解决

当前测试环境
springboot 1.5.4
jdk: Java HotSpot(TM) 64-Bit Server VM (build 25.25-b02, mixed mode)
WebLogic Server 版本: 12.1.3.0.0

可以默认直接跑通JPUSH SDK API，不需要添加自定义SSL证书
## 测试url
```
http://localhost:7001/spring-boot-weblogic-demo/hello?name=test123
```
## 编译工程
```
mvn clean package
```
## 使用docker的方式启动weblogic服务
How To Use:
```
docker pull ismaleiva90/weblogic12
```
To start the docker machine with 7001, 7002 and 5556 ports opened:
```
docker run -d -p 7001:7001 -p 7002:7002 -p 5556:5556 ismaleiva90/weblogic12:latest
```
Web Console
```
http://localhost:49163/console
User: weblogic
Pass: welcome1
```
