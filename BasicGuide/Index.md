
# [Erlang程序设计] - 知识体系规划v1 - 入门基础部分

## 1. Erlang语言简介

### 1.1 Erlang语言开发历史

介绍Erlang语言的开发演进历史，以便学院了解Erlang语言设计目的，要解决的目标问题，简单的对比Ruby等其他语言的历史。

爱立信、Joe Armstrong、爱立信项目、多核心CPU诞生、互联网应用等。

### 1.2 Erlang语言的特点

 0) Erlang语言与其他语言简单对比

 1) 函数编程, 模式匹配

 2) 并发编程, 轻量进程(Process)

 3) 软实时, 低延时, 公平调度

 4) 分布式编程

 5) 容错(Fault-Tolerant)


### 1.3 Erlang语言的适用项目

 服务端程序设计

 适用场景:

 1) 软实时、低延时、分布式消息应用，
 2) 电信设备系统，电信管理系统
 3)互联网
 4)移动互联网
 5)车联网
 6)工业自动化...

### 1.4 为什么应该学习Erlang语言

 1) 完全不同的语言设计思路
 2) .......
 3) 开发生产率高
 4) .......

## 2. Erlang语言开发环境准备

### 2.1) Windows, Linux, Mac下载安装Erlang

  erlang.org下载、编译、安装

### 2.2) erl shell命令简介，执行简单Erlang语句

  erl
  5 + 6.
  
### 2.3) Git客户端、Rebar程序安装，创建简单Erlang项目

  Git客户端
  Rebar安装
  Rebar常用命令
  
### 2.4) Erlang常用开发编辑器、IDE

  vim

  emacs

  http://ignatov.github.io/intellij-erlang/

### 2.5) Erlang开发常用网站

    官网: erlang.org
    Doc: 
    API: erldocs.com
    书籍: <<Programming Erlang>>
    在线: Learnyousomeerlang.com
    github项目: https://github.com/trending?l=erlang
    awesome-erlang: https://github.com/drobakowski/awesome-erlang


## 3. Erlang语言基本概念与数据类型

    3.1) Hello World 
        erl shell输出
        erlc文件编译、执行、path
        erl 程序执行

    3.2) 整数(Numbers)与简单加减乘除

    3.3) 变量(Variables)、一次赋值与匹配
        
    3.4) 原子(Atoms)

    3.5) 布尔(Boolean)与比较操作符(Comparison Operators)

    3.6) Tuples
     ??翻译?

    3.7) 列表(Lists)

    3.8) Dict, Map

    3.9) Binary
    
    翻译?

## 4. Erlang模块(Module)

    对比Java Class类文件, Erlang程序静态上由模块、函数组成

    What are modules, to store code
    Module Declaration
    Compiling the Code
    More About Modules
    Atrributs属性
    Commets注释


## 5 Erlang函数(Function)
    函数编程、模式匹配
    Pattern Matching
    Guards, Guards!
    What the If!?
    In Case ... of
    BIF
    Which to use?

## 6. Erlang Record与头文件
   
    Record定义和适用
    头文件定义

## 7. try...catch异常处理

    case catch
    try...catch
    Stack trace
    编程原则, 少用
    编程原则, 少用

## 8. Erlang程序编译与执行
    erlc编译，src目录、ebin目录、include目录、priv目录
    rebar创建项目、编译


