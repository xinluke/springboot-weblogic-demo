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
