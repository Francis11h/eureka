# eureka

## **Microservices**

EureKa Server 
注册中心 好比 老师手中的名单 记录的是 所有同学的名字, 要点名的时候 就掏出那份名单

微服务中的呢: 它**记录着所有应用的信息和状态（应用的名字 再哪台服务器上 目前是不是正常工作 等）**

微服务中 习惯把一个应用说成一个服务 某某应用 某某服务 说的是同一个东西

eureka 英文单词的意思： 找到了！有了！   注册发现 就是找到了的意思。。。


![eureka register](https://github.com/Francis11h/eureka/blob/master/img-storage/1.png)



## **打包**
由于每次都要开 eureka server 但每次进ide里再开 太麻烦了 于是我们可以去 eureka server目录下 打包 打成一个jar包
命令 ***mvn clean package*** 
![打包命令](https://github.com/Francis11h/eureka/blob/master/img-storage/2.png)
打完的jar包在target文件夹中
进入该文件夹 再用java 命令 ***java -jar target/eureka-0.0.1-SNAPSHOT.jar*** 启动下 
![启动](https://github.com/Francis11h/eureka/blob/master/img-storage/3.png)

## 设置后台进程启动

Eureka Client


