## 1. 完成基于HTTPS的服务
## 2. 完成HTTP向HTTPS的自动跳转
## 3. 自签证书生成

在项目的根下键入：
```shell script
spring-boot_https $ keytool -genkey  -keyalg RSA -keystore ./server.keystore
```
