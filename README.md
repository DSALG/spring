# spring
spring源码学习笔记
(1)Core Container: 
core模块:spring的核心工具类。

beans模块:访问配置文件，创建和管理bean以及进行IOC/DI操作。

context模块:构建与beans和core之上，提供一种类似于JNDI注册器的框架式的对象访问方法，增加了对国际化、事件传播、资源加载和对Context的透明创建的支持 ，支持J2EE的一些特性，如EJB,JMX和基础的远程处理。

Expression Langauage模块:一个强大的表达式语言用于在运行时查询和操纵对象。支持设置/获取属性的值，属性的分配，方法的调用，访问数组上下文、容器和索引器、逻辑和算术运算符、命名变量以及从Spring的IOC容器中根据名称检索对象，支持list投影、选择和一般的list聚合。

(2)Data Access/Integration:
JDBC模块:
ORM模块:
OXM模块:
JMS(Java Messaging Service)模块:
Transaction模块:

(3)Web



(4)AOP
Aspects模块:
Instrumentation模块:提供class instrumentation 支持和classloader实现，使得可以在特定的应用服务器上使用

(5)Test
Test模块支持使用Junit和TestNG对Spring组件进行测试


