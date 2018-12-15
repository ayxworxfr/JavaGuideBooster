# JavaGuide (还在整理中，请耐心等待，如果急需相关资料，请邮箱联系我)
<a href="#1"><<Java应届生面试突击>></a> <br>
<a href="#2"><<Java工程师面试突击>></a>

# 目录
<a href="#1"><<Java应届生面试突击>></a> <br>
&ensp;&ensp; <a href="#11">Java基础</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#111">JVM相关</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#112">Java中的集合类</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#113">设计模式相关</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#114">Java语言相关</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#115">Java基础专题</a> <br>

&ensp;&ensp; <a href="#12">多线程和并发</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#121">多线程和并发专题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#122">并发包的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#123">阻塞队列相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#124">多线程相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#125">其他问题</a> <br>

&ensp;&ensp;  <a href="#13">数据库</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#131">数据库专题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#132">sql 注入的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#133">连接问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#134">存储过程相关问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#135">范式问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#136">事务问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#137">锁的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#138">命令问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#139">索引问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#1310">存储引擎问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#1311">其他问题</a> <br>

&ensp;&ensp;  <a href="#14">操作系统</a> <br> 
&ensp;&ensp; ♦ <a href="#141">操作系统专题</a> <br>

&ensp;&ensp;  <a href="#15">计算机网络</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#15">TCP/IP相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#15">HTTP 协议相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#15">安全相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#15">Socket 编程</a> <br>
&ensp;&ensp;&ensp;&ensp; ♦ <a href="#15">其他相关的问题</a> <br>

<a href="#2"><<Java工程师面试突击>></a> <br>
&ensp;&ensp;  <a href="#21">消息中间件</a> <br>
&ensp;&ensp;  <a href="#22">分布式搜索</a> <br>
&ensp;&ensp;  <a href="#23">分布式缓存</a> <br>
&ensp;&ensp;  <a href="#24">分布式系统</a> <br>
&ensp;&ensp;  <a href="#25">数据库</a> <br>

### <a name="1">Java应届生面试突击</a>

---
#### <a name="11">Java基础</a>
&ensp;&ensp; ♦ <a name="111">JVM相关</a> <br>
&ensp;&ensp;&ensp;&ensp; • [1. 说一下Java的垃圾回收机制。]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. JVM的内存布局内存模型。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. JVM 的 4 种引用和使用场景?]() <br>
&ensp;&ensp;&ensp;&ensp; • [4. 说一下引用计数法与可达性分析算法。]() <br>
&ensp;&ensp;&ensp;&ensp; • [5. 如何判断对象是不是垃圾?]() <br>
&ensp;&ensp;&ensp;&ensp; • [6. 堆里面的分区和各自的特点。]() <br>
&ensp;&ensp;&ensp;&ensp; • [7. Minor GC 与 Full GC 分别在什么时候发生?]() <br>
&ensp;&ensp;&ensp;&ensp; • [8. 对象创建方法,对象的内存布局,对象的访问定位。]() <br>
&ensp;&ensp;&ensp;&ensp; • [9. 说一下几种垃圾收集算法的原理和特点,应用的场景。怎么优化复制算法?]() <br>
&ensp;&ensp;&ensp;&ensp; • [10. GC 收集器有哪些?CMS 收集器与 G1 收集器的特点。]() <br>
&ensp;&ensp;&ensp;&ensp; • [11. 什么是内存泄露和内存溢出。]() <br>
&ensp;&ensp;&ensp;&ensp; • [12. 如何减少 gc 出现的次数(java 内存管理)。(重点!!!!)]() <br>
&ensp;&ensp;&ensp;&ensp; • [13. 数组多大放在 JVM 老年代? 永久代对象如何 GC?如果想不被 GC 怎么办?如果想在 GC 中生存 1 次怎么办?]() <br>
&ensp;&ensp;&ensp;&ensp; • [14. JVM 常见的启动参数。]() <br>
&ensp;&ensp;&ensp;&ensp; • [15. 说下几种常用的内存调试工具: jps、 jmap、 jhat、 jstack、 jconsole,jstat。]() <br>
&ensp;&ensp;&ensp;&ensp; • [16. 说下虚拟机的类加载机制。]() <br>
&ensp;&ensp;&ensp;&ensp; • [17. 说下双亲委派模型。双亲委派模型中有哪些方法。用户如何自定义类加载器 。怎么打破双亲委托机制?]() <br>
&ensp;&ensp;&ensp;&ensp; • [18. 描述 Java 类加载器的工作原理及其组织结构。]() <br>
&ensp;&ensp;&ensp;&ensp; • [21. Java 编译的过程。]() <br>
&ensp;&ensp;&ensp;&ensp; • [22. class 文件是什么类型文件(字节码文件的格式)?]() <br>
&ensp;&ensp;&ensp;&ensp; • [23. 即时编译器的优化方法。]() <br>
&ensp;&ensp;&ensp;&ensp; • [24. 静态分派与动态分派。]() <br>
&ensp;&ensp;&ensp;&ensp; • [25. 编译阶段对程序做了哪些优化?]() <br>
&ensp;&ensp;&ensp;&ensp; • [26. new 的对象如何不分配在堆而分配在栈上?]() <br>

&ensp;&ensp; ♦ <a name="112">Java中的集合类</a> <br>
&ensp;&ensp;&ensp;&ensp; • [1. ArrayList、LinkedList、Vector 的区别和实现原理。]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. HashMap、HashTable、LindedHashMap、ConcurrentHashMap、WeakHashMap 的区别和实现原理。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. 讲一下集合中的 fail-fast 机制。]() <br>
&ensp;&ensp;&ensp;&ensp; • [4. 介绍一下 Java 中的集合框架?]() <br>
&ensp;&ensp;&ensp;&ensp; • [5. Collection 包结构与 Collections 的区别。]() <br>

&ensp;&ensp; ♦ <a name="113">设计模式相关</a> <br>
&ensp;&ensp;&ensp;&ensp; • [1. 编写线程安全的单例模式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. 享元模式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. 原型模式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [1. 观察者设计模式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. 装饰者设计模式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. 工厂设计模式。]() <br>

&ensp;&ensp; ♦ <a name="114">Java语言相关</a> <br>
&ensp;&ensp;&ensp;&ensp; • [1. 标识符的命名规则。]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. instanceof 关键字的作用。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. strictfp 关键字的作用。]() <br>
&ensp;&ensp;&ensp;&ensp; • [4. 什么是不可变类?]() <br>
&ensp;&ensp;&ensp;&ensp; • [5. Java 中的基本数据类型占据几个字节?]() <br>
&ensp;&ensp;&ensp;&ensp; • [6. 运算符的优先级。]() <br>
&ensp;&ensp;&ensp;&ensp; • [7. 强制类型转换时的规则有哪些。]() <br>
&ensp;&ensp;&ensp;&ensp; • [8. 数组初始化时需要注意的问题。]() <br>
&ensp;&ensp;&ensp;&ensp; • [9. 如何在 main()方法执行前输出“Hello world”?]() <br>
&ensp;&ensp;&ensp;&ensp; • [10. Java 程序初始化的顺序(对象实例化的过程)。]() <br>
&ensp;&ensp;&ensp;&ensp; • [11. 构造函数的特点。]() <br>
&ensp;&ensp;&ensp;&ensp; • [12. 序列化与反序列化。]() <br>
&ensp;&ensp;&ensp;&ensp; • [13. Switch 能否用 string 做参数?]() <br>
&ensp;&ensp;&ensp;&ensp; • [14. equals 与==的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [15. Hashcode 的作用。]() <br>
&ensp;&ensp;&ensp;&ensp; • [16. hashCode() 与 equals() 生成算法、方法怎么重写。]() <br>
&ensp;&ensp;&ensp;&ensp; • [17. Object 有哪些公用方法?]() <br>
&ensp;&ensp;&ensp;&ensp; • [18. String、StringBuffer 与 StringBuilder 的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [19. try catch finally,try 里有 return,finally 还执行么?如果会的话,什么时候执行,在 return 之前还是 return 之后?]() <br>
&ensp;&ensp;&ensp;&ensp; • [20. 说下异常的原理。]() <br>
&ensp;&ensp;&ensp;&ensp; • [21. Java 面向对象的三个特征与含义。]() <br>
&ensp;&ensp;&ensp;&ensp; • [22. java 多态的实现原理(实现机制)。]() <br>
&ensp;&ensp;&ensp;&ensp; • [23. Override(覆盖、重写)和 Overload(重载)的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [24. 接口与抽象类的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [25. 静态内部类和非静态内部类的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [26. static 的使用方式。]() <br>
&ensp;&ensp;&ensp;&ensp; • [27. 反射的作用与原理。如何提高反射效率?]() <br>
&ensp;&ensp;&ensp;&ensp; • [28. Java 和 C++/C 的区别,JAVA 的优点。]() <br>
&ensp;&ensp;&ensp;&ensp; • [29. 同一个.java 文件中是否可以有多个 main()方法?]() <br>
&ensp;&ensp;&ensp;&ensp; • [30. JAVA 中的类和成员的访问控制。]() <br>
&ensp;&ensp;&ensp;&ensp; • [31. System.out.println()方法使用时需要注意的问题。]() <br>
&ensp;&ensp;&ensp;&ensp; • [32. 继承和组合区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [33. final finally finalize 的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [34. JDK1.7 和 1.8 的区别。]() <br>
&ensp;&ensp;&ensp;&ensp; • [35. List<String>能否转为List<Object>?能否List<Object>list=newArrayList<String>()?List<String>list=new ArrayList<Object>()?原因?]()<br>
&ensp;&ensp;&ensp;&ensp; • [36. 泛型的好处?]() <br>

&ensp;&ensp; ♦ <a name="115">Java基础专题</a> <br>
&ensp;&ensp;&ensp;&ensp; • [1. String 中的”+”操作是怎么回事?]() <br>
&ensp;&ensp;&ensp;&ensp; • [2. StringBuilder 和 StringBuffer 底层是怎么实现的。]() <br>
&ensp;&ensp;&ensp;&ensp; • [3. String 类中常用的方法。]() <br>
&ensp;&ensp;&ensp;&ensp; • [4. 创建虚引用的时候,构造方法传入一个 ReferenceQueue,作用是什么。]() <br>
&ensp;&ensp;&ensp;&ensp; • [5. 栈溢出的原因和解决方法。]() <br>
&ensp;&ensp;&ensp;&ensp; • [6. HashMap的加载因子的作用。]() <br>
&ensp;&ensp;&ensp;&ensp; • [7. HashMap中的 key 可以是任意对象吗?(Set 中元素的内容可以改变吗?)]() <br>
&ensp;&ensp;&ensp;&ensp; • [8. 如果你定义一个类,包括学号,姓名,分数,如何把这个对象作为 key?]() <br>
&ensp;&ensp;&ensp;&ensp; • [9. java是如何实现跨平台的。]() <br>
&ensp;&ensp;&ensp;&ensp; • [10. 什么是泛型,为什么要使用以及类型擦除。]() <br>
&ensp;&ensp;&ensp;&ensp; • [11. Java中的 NIO,BIO 分别是什么。NIO 主要用来解决什么问题。]() <br>
&ensp;&ensp;&ensp;&ensp; • [12. 面向对象的 6 个基本原则(设计模式的 6 个基本原则)。]() <br>
&ensp;&ensp;&ensp;&ensp; • [13. JDK 源码中用到的设计模式 。]() <br>              
&ensp;&ensp;&ensp;&ensp; • [14. 执行 Student s = new Student();在内存中做了哪些事情?]() <br>
&ensp;&ensp;&ensp;&ensp; • [15. 你知道的开源软件有哪些?]() <br>
&ensp;&ensp;&ensp;&ensp; • [16. String 型变量如何转成 int 型变量,反过来呢?]() <br>
&ensp;&ensp;&ensp;&ensp; • [17. 怎么判断数组是 null 还是为空?]() <br>
&ensp;&ensp;&ensp;&ensp; • [18. 怎样让一个线程放弃锁。]() <br>
&ensp;&ensp;&ensp;&ensp; • [19. IO 里面常见的类。]() <br>
&ensp;&ensp;&ensp;&ensp; • [20. xml 解析方式。]() <br>
                                 
#### <a name="12">多线程和并发</a>
&ensp;&ensp; ♦ <a name="121">多线程和并发专题</a>[]() <br>
&ensp;&ensp;&ensp;&ensp; • [1. 什么是缓存一致性问题?如何解决呢?]() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>
&ensp;&ensp; ♦ <a name="122">并发包的问题</a> <br>
&ensp;&ensp; ♦ <a name="123">阻塞队列相关的问题</a> <br>
&ensp;&ensp; ♦ <a name="124">多线程相关的问题</a> <br>
&ensp;&ensp; ♦ <a name="125">其他问题</a> <br>

#### <a name="13">数据库</a>
&ensp;&ensp; ♦ <a name="131">数据库专题</a> <br>
&ensp;&ensp; ♦ <a name="132">sql 注入的问题</a> <br>
&ensp;&ensp; ♦ <a name="133">连接问题</a> <br>
&ensp;&ensp; ♦ <a name="134">存储过程相关问题</a> <br>
&ensp;&ensp; ♦ <a name="135">范式问题</a> <br>
&ensp;&ensp; ♦ <a name="136">事务问题</a> <br>
&ensp;&ensp; ♦ <a name="137">锁的问题</a> <br>
&ensp;&ensp; ♦ <a name="138">命令问题</a> <br>
&ensp;&ensp; ♦ <a name="139">索引问题</a> <br>
&ensp;&ensp; ♦ <a name="1310">存储引擎问题</a> <br>
&ensp;&ensp; ♦ <a name="1322">其他问题</a> <br>

#### <a name="14">操作系统</a>
&ensp;&ensp; ♦ <a name="141">操作系统专题</a> <br>
&ensp;&ensp;&ensp;&ensp; • []() <br>

#### <a name="15">计算机网络</a>
&ensp;&ensp; ♦ <a name="151">TCP/IP相关的问题</a> <br>
&ensp;&ensp;&ensp;&ensp; • <a name="15">OSI与TCP/IP各层的结构与功能,都有哪些协议,协所占端口号。</a> <br>
&ensp;&ensp; ♦ <a name="152">HTTP协议相关的问题</a> <br>
&ensp;&ensp; ♦ <a name="153">安全相关的问题</a> <br>
&ensp;&ensp; ♦ <a name="154">Socket编程</a> <br>
&ensp;&ensp; ♦ <a name="155">其他相关的问题</a> <br>

### <a name="2">Java工程师面试突击</a>
--- 
#### <a name="21">消息中间件</a>
- [如何进行消息队列的选型]()
- [引入消息队列后如何保证其可用性]()
- [为什么消息队列里消费到了重复数据]()
- [发到消息队列的数据不见了]()
- [如何保证从消息队列拿到的数据按照顺序执行]()
- [几百万消息在小消息队列里积压了几小时]()
- [如果让你开发一个消息中间件,你会怎么设计架构]()
- [消息队列相关问题的面试技巧]()

#### <a name="22">分布式搜索</a>
- [分布式引擎架构是怎么设计的,为什么是分布式的]()
- [分布式搜索引擎写入和查询的工作流程]()
- [分布式搜索引擎在几十亿数据量级的场景下如何优化查询性能]()
- [你们公司分布式搜索引擎是怎么部署的]()
- [分布式搜索引擎相关问题的面试技巧]()

#### <a name="23">分布式缓存</a>
- [分布式缓存第一个问题]()
- [redis线程模型,为什么单线程还是有很高的效率]()
- [redis有哪些数据类型,分别在什么场景下使用比较合适]()
- [redis过期策略,手写LRU]()
- [怎么保证redis是高并发和高可用]()
- [怎么保证redis挂掉之后再重启数据可以恢复]()
- [redis cluster集群模式的原理]()
- [一般如何应对缓存雪崩以及穿透问题]()
- [如何保证缓存与数据库双写时的数据一致性]()
- [redis的并发竞争该如何解决]()
- [你们公司生产环境的redis集群的部署架构是什么样的]()
- [分布式缓存面试题的回答技巧]()

#### <a name="24">分布式系统</a>
- [为什么要把系统拆分为分布式,为啥要用dubbo]()
- [dubbo的工作原理,注册中心挂了可以继续通信嘛]()
- [dubbo都支持哪写通信协议以及序列化协议]()
- [dubbo支持哪写负载均衡,高可用以及动态代理策略]()
- [SPI是啥意思,dubbo的SPI机制原理]()
- [基于dubbo如何做服务治理、服务降级以及重试]()
- [分布式接口的幂等性如何保证,比如不能重复扣款]()
- [分布式系统中的接口调用如何保证顺序性]()
- [如何设计一个类似dubbo的rpc框架,架构上如何考虑]()
- [zookeeper一般都有哪写使用场景]()
- [什么是分布式锁,对比redis和zk两种分布式锁的优劣]()
- [说说你们的分布式session方案,怎么做的]()
- [分布式事务方案,有啥坑]()
- [一般如何设计一个高并发的系统架构]()

#### <a name="25">数据库</a>
- [如何分库分表]()
- [如何系统不停机迁移到分库分表]()
- [如何设计可动态扩容缩容的分库分表方案]()
- [分库分表后全局id如何生成]()
- [MySQL读写分离的原理,主从同步如何解决]()


    