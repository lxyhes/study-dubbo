# 学习Dubbo
## Dubbo官方文档
http://dubbo.apache.org/zh/


## zookeeper安装步骤（windows版本）
### 1、首先下载zookeeper
http://mirror.bit.edu.cn/apache/zookeeper/zookeeper-3.5.8/


选择带bin的哪一个
 apache-zookeeper-3.6.2-bin.tar.gz
 
 
 ### 2、配置
 将apache-zookeeper-3.6.2-bin/config文件夹下的zoo_sample.cfg 复制一份命名为zoo.cfg
 
 
 ### 3、启动
 打开文件夹apache-zookeeper-3.6.2-bin/bin
Mac执行命令行执行 ./zkServer.sh start
Windows同学执行对应的cmd文件

出现下面这个代表启动成功

$ ./zkServer.sh start
ZooKeeper JMX enabled by default
Using config: E:\IdeaProduct\3,study-class-workspace\2，study-mooc-javajiagou-project\apache-zookeeper-3.5.8-bin\apache-zookeeper-3.5.8-bin\conf\zoo.cfg
Starting zookeeper ... STARTED

