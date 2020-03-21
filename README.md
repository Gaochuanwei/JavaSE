# 第二章	变量、数据类型和运算符

## 2.1 变量的概念

- 电脑使用内存来记忆计算时所使用的数据

- 内存如何存储数据

  ![1583236401985](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1583236401985.png)

- 内存像旅馆

  - 数据各式各样
  - 根据数据的需求（即类型）为它申请一块合适的空间

- 内存地址不好记，怎么办？

  - 通过内存中小房间的别名找到数据存储的位置

    ![1583236543261](C:\Users\Administrator\AppData\Roaming\Typora\typora-user-images\1583236543261.png)

  - 通过变量名可以简单快速地找到它存储的数据

## 2.2 Java常用数据类型

Java基本数据类型：

- 数值类型(4类8种)
  - 整型
    - byte
    - short
    - int
    - long
  - 浮点型
    - float
    - double
  - 布尔型
    - boolean
  - 字符型
    - char
- 非数值类型（引用类型）
  - 对象
  - 数组

## 2.3 赋值运算符、算术运算符

- 赋值运算符

```java
变量名 = 表达式;
```

- 算数运算符

```java
+ - * / %
```



## 2.4 boolean类型和关系运算符

关系运算符

```java
> < >= <= == !=
```



## 2.5 数据类型转换

数据类型转换规则

- 规则1：如果一个操作数为double型，则整个表达式可提升为double型
- 规则2：满足自动类型转换的条件
  - 两种类型要兼容
    - 数值类型（整型和浮点型）互相兼容
  - 目标类型大于源类型
    - 例如：double 型大于 int 型

强制类型转换

```java
(类型名)表达式
```



## 2.6 键盘输入

Scannner

```java
int a;
Scanner in=new Scanner(System.in);
a=in.nextInt();
```

