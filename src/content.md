#一、	Java基础
##1.1	线程
进程、线程与任务  
线程的创建、启动与运行  
线程的生命周期状态  
串行、并发与并行  
竞态  
线程安全：原子性、可见性、有序性  
线程池  
整个并发体系  
##1.2	锁
synchronized 关键字  
volatile关键字（轻量同步机制）  
如何解决线程死锁  
锁的分类  
锁膨胀与锁降级  
CAS / AQS  

##1.3	JVM、GC
JVM内存模型  
垃圾回收机制  
gc root  
Java的内存结构、堆分为哪几部分，默认年龄多大进入老年代  
JVM内存结构  

##1.4	集合
HashMap  
ConcurrentHashMap  

##1.5 其他
双亲委派模型及其使用场景  
cpu进程占用率很高，如何调优  

##1.6 设计模式

#二、	MySQL
##2.1 索引
数据库索引原理  
索引失效的场景  
最左匹配原则  

##2.2 数据库事务
数据库事务隔离级别：脏读、不可重复读、幻读  

##2.3 数据库锁
数据库锁及其应用场景  
limit值很大时有什么问题  
having的使用场景  
mysql主从复制同步方式  
mysql怎么保证数据不丢失  
#三、	Redis
Redis数据类型  
缓存击穿、缓存穿透、缓存雪崩  
redis集群，缓存A和B不在同一个节点，保证操作的原子性  
Redis实现延时队列  
Redis哈希扩容机制  
零点促销活动，在零点时才公布商品，Redis需要提前做什么操作  
AOF与REWRITE机制  
Redis单线程为什么这么快  
Redis零拷贝  
Redis集群高可用原理，一台挂了，怎么切换到另一台  
Redis的key过期策略  
Redis的集群和选主  

#四、Kafka
Kafka基础  
消息积压如何处理  
消息重复消费如何处理  
消息有序性如何保证  
kafka如何保证消息的可靠性  
Kafka如何保证副本的消息都是最新的  
Kafka如何保证高可用  
Kafka零拷贝  
Kafka水位机制  

#五、框架相关
AOP如何实现（代理模式）（*）  
Spring用到的设计模式  
Spring中打印业务类的创建时间  
Spring中postbeanfactory 和 beanfactory区别  
Spring事务原理 @transactional 事务失效场景  
讲一讲bean 的生命周期（详细）、作用域  
tomcat缓存  

#六、分布式
CAP理论  
数据一致性问题、分布式事务、最终一致性，不借助任何中间件如何实现最终一致性  
如何保证高可用  
如何保证redis和mysql数据一致  
分布式任务中，一个微服务的多个线程报错，如何处理和定位  
如何实现全局的id生成策略（雪花算法）  
分布式锁、Zookeeper如何实现分布式锁  
分布式一致性算法  
服务注册中心宕机怎么办  
分布式事务  
分布式缓存  

#七、前端
Cookie是怎么存储的 Cookie原理  
TCP三次握手 半连接问题  
HTTPS 和 HTTP区别  
访问网页具体流程  
MVCC  
HTTP有哪些问题  

#八、面试问题
如何实现群消息已读  
能不能自己实现一个 java.lang.String  
设计秒杀系统  
如何实现限流  
如何实现定时关单  
进程同步方式  
如何自己实现内存分配和管理  
二分查找 / 冒泡算法 / 快速排序  
十亿条淘宝记录，怎么获取出现最多的前十个  


