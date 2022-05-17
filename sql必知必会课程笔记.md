# SQL必知必会学习笔记

按功能分为4部分：
* DDL（Data Definition Language）
* DML (Data Manipulation Language)
* DCL (Data Control Language)
* DQL (Data Query Language)

## SQL大小写问题
1、表明、表别名、字段名、字段别名等都小写

2、SQL 保留字、函数名、绑定变量等都大写

```
SELECT name, hp_max FROM heros WHERE role_main = '战士'
```