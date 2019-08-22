# Java Core之从字节码深入理解HelloWorld

1. Java中的点：java的基础语法
2. Java中的线：java的核心技术
3. Java中的面：各类封装了底层的框架如：SSH，SSM，S2SH，SHIRO，ACTIVITY等
4. Java中体积：就是灵活使用各个面搭建一个实体（项目）

#### Java与C++和C语言

面向过程：C语言面向过程，主要关注的是数据的流向。

面向对象：C++和Java都是面向对象，主要关注的是不同对象之间如何交互。

Java把C++的复杂语法以及手动释放内存以及容易造成编程错误的指针等弊端屏蔽了。

C语言和C++直接操作内存，而Java通过JVM与操作系统交互，所以C语言和C++不具备可移植性，Java具有移植性。

#### Java运行条件

JDK：Java Develop Kit Java开发工具

JRE：Java Runtime Enviroment Java运行环境

JVM：Java virtual Machine Java虚拟机

首先javac xxx.java通过JDK生成字节码文件xxx.class，此时先校验xxx.class文件是否符合JVM规范，然后通过类加载器在JVM中运行，JVM是在计算机内存中开辟的一块内存空间。

JVM在将类字节码读入到内存中后，会找到加载的类中的主类，然后在主类中找到main方法之后执行main方法。





#### Java，C语言、C++的区别

![1565967714157](D:\hexo\blog\source\Java、C语言、C++的区别.png)





#### 类加载的过程

![1565967796162](D:\hexo\blog\source\类加载过程.png)





#### 对象的创建过程

![1565967830030](D:\hexo\blog\source\对象的创建过程.png)



#### Object的equals()、toSttring()方法、native关键字

![](D:\hexo\blog\source\Object的equals方法、toString方法，以及native关键字.png)



#### 常量池

![](D:\hexo\blog\source\常量池.png)



#### Java知识体系

![Java知识体系](D:\hexo\blog\source\Java知识体系.png)



#### 集合

![集合](D:\hexo\blog\source\集合.png)



#### String

![String](D:\hexo\blog\source\String.png)



#### 方法调用

![方法调用](D:\hexo\blog\source\方法调用.png)



#### 方法重载

![方法重载](D:\hexo\blog\source\方法重载.png)

##### 为什么Java中重载是以方法名和参数作为方法的描述符的？

答：在方法执行中有时候只关心方法的执行过程，而不关心方法的返回值，所以我们用方法名和参数作为方法的描述符。



#### javap -verbose xxx  查看字节码（反编译）





