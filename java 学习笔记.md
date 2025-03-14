# java 学习笔记

## 命令行窗口的常见命令

1. D：  切换到某个盘下：D：，C:

2. dir  查看当前路径下的文件信息

3. cd  

   1. 进入单极目录：cd 目录名

   2. 进入多极目录：cd D:\目录名\目录名\目录名

   3. 回退到上一级目录：cd ..
   4. 回退到盘符根目录：cd\

4. cls  清屏

需要先切盘才能cd到某个目录中

键盘上的tab键是用于补全

鼠标右键用于粘贴

## 编写程序的基本步骤

1. 编写代码，（文件名.java）这是源代码文件

2. 用javac进行编译

   ```
   javac 文件名.java
   ```

3. 运行

   ```
   java 文件名
   ```


## JDK的组成

jvm:java虚拟机，真正运行java程序的地方

核心类库：java自己写好的程序，给程序员自己的程序调用的

jvm和核心类库统称JRE:java的运行环境

java和javac是java的开发工具

## path环境变量

path环境变量用于记住程序路径，方便在命令行窗口的任意目录启动程序

## 配置java_home环境变量

告诉操作系统JDK安装在了哪个位置

## 使用IDEA开发程序

新建空工程(Porject)，新建模块(Module),新建包(Package),新建类(class)，编写代码

编译好的文件位于out文件夹中

## 类型转换

1. 自动类型转换，类型范围小的变量可以直接赋值给范围大的变量。

![image-20250209160020501](C:\Users\shdn\AppData\Roaming\Typora\typora-user-images\image-20250209160020501.png)

2. 表达式的自动类型转换，在表达式中，小范围类型的变量，会自动转换成表达式中较大范围的类型，在参与运算。

![image-20250209160502453](C:\Users\shdn\AppData\Roaming\Typora\typora-user-images\image-20250209160502453.png)

3. 强制类型转换，强制将范围大的变量转换为范围小的变量。



​    







