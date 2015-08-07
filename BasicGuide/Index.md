
# [Erlang/OTP程序设计] - 知识体系规划v1 - 入门基础部分

## 1. Erlang编程语言简介

### 1.1 Erlang编程语言历史(8-10分钟)

    介绍Erlang语言的开发演进历史，以便学员了解Erlang语言设计目的，要解决的问题，简单的对比Ruby等其他语言的历史。

    爱立信、Joe Armstrong、爱立信项目、多核心CPU诞生、互联网应用等。


### 1.2 Erlang编程语言特点(12分钟)

    0) 为什么应该学习Erlang语言
      
      不同的语言设计思路，与C, C++, Java, C#, PHP完全不同的设计思路
      开发生产率
      大规模连接的服务端程序
      分布式系统

    1) 函数编程, 模式匹配，尾递归

    2) 并发编程, 轻量进程(Process)

    3) 软实时, 低延时, 公平调度

    4) 分布式编程

    5) 容错(Fault-Tolerant)


### 1.3 Erlang语言的适用项目

    服务端程序设计

    适用场景:

    1) 软实时、低延时、分布式消息应用，
    2) 电信设备系统，电信管理系统
    3) 游戏编程
    4) 互联网
    5) 移动互联网
    6) 物联网、工业自动化...

## 2. Erlang语言开发环境准备

### 2.1 Windows, Linux, Mac下载安装Erlang(5~8分钟)

    erlang.org下载、编译、安装

### 2.2 erl shell命令简介，执行简单Erlang语句

    erl
    5 + 6.
  
### 2.3 Git客户端、Rebar程序安装，创建简单Erlang项目

    Git客户端
    Rebar安装
    Rebar常用命令
  
### 2.4 Erlang常用开发编辑器、IDE

    vim
    emacs
    http://ignatov.github.io/intellij-erlang/

### 2.5 Erlang开发常用网站

    官网: erlang.org
    官网文档: http://www.erlang.org/doc.html
    API: erldocs.com
    书籍: <<Programming Erlang>>
    在线: Learnyousomeerlang.com
    github项目: https://github.com/trending?l=erlang
    awesome-erlang: https://github.com/drobakowski/awesome-erlang


## 3. 开始学习Erlang语言(15分钟)

### 3.1 Hello World程序
    erl shell输出
    erlc文件编译、执行、path
    erl 程序执行

### 3.2 整数(Numbers)与简单四则运算

### 3.3 变量(Variables)、一次赋值与模式匹配

....


## 4. Erlang编程语言简单数据类型

### 4.1 整数与浮点

### 4.2 原子(Atom)

### 4.3 布尔(Boolean)与比较操作符(Comparison Operators)

### 4.4 PID(进程Id)
    
### 4.5 Referrence

### 4.6 Port ???

....


## 5. Erlang语言复合数据类型

### 5.1 元祖(Tuple), 记录(Record)

### 5.2 列表(List)介绍

### 5.3 列表(List)操作

### 5.4 列表(List Comprehension)

### 5.5 Dict, Map

### 5.6 Binary(字节数组)

....


## 6. Erlang模块(Module)

    0) 对比Java Class类文件, Erlang程序静态上由模块、函数组成

    1) 模块声明、属性、函数定义、注释 
    
    What are modules, to store code
    Module Declaration
    Compiling the Code
    More About Modules
    Atrributs属性
    Commets注释

## 7. Erlang函数(Function)

### 7.1  函数编程、函数Export/Import, 函数定义, 模式匹配
    Pattern Matching

### 7.2 函数Guards

### 7.3 IfElse语句

### 7.4 Case语句

### 7.5 For循环? 尾递归!

### 7.6 BIF函数


## 8. Erlang头文件
   
    Record定义和适用
    头文件定义
    include头文件


## 9. try...catch异常处理

    case catch
    try...catch
    Stack trace
    编程原则, 少用
    编程原则, 少用


## 10. Erlang程序编译与执行

    1) 一个简单的Erlang程序
    2) erlc编译，src目录、ebin目录、include目录、priv目录
    3) erl

