# czy-study-jvm
之前学习的jvm笔记整理到这里，方便大家学习


## Java与JVM介绍
          JVM是Java Virtual Machine（Java虚拟机）的缩写，JVM是一种用于计算设备的规范，它是一个虚构出来的计算机，
    是通过在实际的计算机上仿真模拟各种计算机功能来实现的。
    
          Java语言的一个非常重要的特点就是与平台的无关性。而使用Java虚拟机是实现这一特点的关键。一般的高级语言如果要
    在不同的平台上运行，至少需要编译成不同的目标代码。而引入Java语言虚拟机后，Java语言在不同平台上运行时不需要重新编译。
    Java语言使用Java虚拟机屏蔽了与具体平台相关的信息，使得Java语言编译程序只需生成在Java虚拟机上运行的目标代码（字节码），
    就可以在多种平台上不加修改地运行。Java虚拟机在执行字节码时，把字节码解释成具体平台上的机器指令执行。这就是Java的
    能够“一次编译，到处运行”的原因。

## JVM内部结构
![](https://github.com/andyczy/czy-study-jvm/blob/master/img/JVM%E5%86%85%E9%83%A8%E7%BB%93%E6%9E%84.png "JVM内部结构")

## Java class执行过程 
![](https://github.com/andyczy/czy-study-jvm/blob/master/img/Java%20class%E6%89%A7%E8%A1%8C%E8%BF%87%E7%A8%8B.png "Java class执行过程")

## 类加载器两种类型
![](https://github.com/andyczy/czy-study-jvm/blob/master/img/%E4%B8%A4%E7%A7%8D%E7%B1%BB%E5%9E%8B%E7%9A%84%E7%B1%BB%E5%8A%A0%E8%BD%BD%E5%99%A8.png)