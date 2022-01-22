﻿# kafka-install
##下载地址
https://kafka.apache.org/downloads

需要安装有JAVA JDK，直接使用最新版本 https://www.oracle.com/java/technologies/downloads/


参考链接

https://www.cnblogs.com/shej123/p/10277653.html

https://www.cnblogs.com/flower1990/p/7466882.html

## window
### 下载
3.0.0有bug，使用2.8.1，启动时目录不能有空格，故不能将解压目录放到`Program Files`目录下

https://archive.apache.org/dist/kafka/2.8.1/kafka_2.13-2.8.1.tgz

下载解压
### 启动
使用`window PowerShell`

#### 启动zookeeper
```
cd D:\kafka_2.13-2.8.1\bin\windows
.\zookeeper-server-start.bat ..\..\config\zookeeper.properties
```
#### 启动kafka
```
cd D:\kafka_2.13-2.8.1\bin\windows
 .\kafka-server-start.bat ..\..\config\server.properties
```
