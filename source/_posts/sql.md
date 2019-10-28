---
title: SQL、NoSQL、NewSQL 看这篇文章就够了
date: 2019-10-28 12:31:22
tags:
- SQL
- NoSQL
- NewSQL
- 数据库
categories:
- 数据库
---
![](http://pztl2fha9.bkt.clouddn.com/art-big-data-blur-373543.jpg)


## 前言

技术一直在发展，随着这个月阿里的 OceanBase 砍获数据库世界第一，远超 Oracle

很多人开始关注数据库的发展方向

![](http://pztl2fha9.bkt.clouddn.com/6af89bc8gw1f8rgblk2npj208m07r0sq.jpg)

但是祺老弟求求大佬们别再提什么新概念新名称了！学不来！！

![](http://pztl2fha9.bkt.clouddn.com/9150e4e5gw1f9f2zzbwtuj205i03zt8s.jpg)

但是逼总是要装的，今天我们就一起看看这些新出的名词都是些什么

## SQL

SQL 就不用祺老弟多讲了，是传统的关系型数据库，70年代以来，它一直是主要的数据库解决方案

![](http://pztl2fha9.bkt.clouddn.com/ac6eddc451da81cb037c289d5366d016082431c3.jpg)

![](http://pztl2fha9.bkt.clouddn.com/u=1545840296,2560930675&fm=26&gp=0.jpg)

优点：

- 使用统一标准的语言
- 坚持 ACID 准则

所以一般企业都离不开 SQL，更是诞生了像是 DBA (数据库管理员) 专门处理优化数据库的职业

但是互联网发展到现在，像是 Google、阿里、百度等巨头的数据起码也达到 PB，甚至是 EB 的级别，单纯依赖传统的 SQL 注定是被淘汰的

![](http://pztl2fha9.bkt.clouddn.com/9150e4e5ly1fcsmsy8gx4j206o06o0t4.jpg)

## NoSQL

所以近些年就有了 NoSQL（Not Only SQL）的出现，它主要用于解决 SQL 的可扩展性问题

![](http://pztl2fha9.bkt.clouddn.com/u=2437443776,3423398538&fm=26&gp=0.jpg)

![](http://pztl2fha9.bkt.clouddn.com/timg.jpg)

优点：

- 灵活的数据模型
- 易扩展性
- 高可用性

NoSQL 采用列式存储、健值和文档存储来存储数据，而 SQL 只能通过表结构，这样大大的提现了 NoSQL 灵活的数据模型

而且面对日益增多的数据，传统的 SQL 性能受限于磁盘 IO，像是 Redis 这种内存型数据库正好解决这种性能瓶颈

但是

![](http://pztl2fha9.bkt.clouddn.com/006ARE9vgy1fz1ugkmbrej30k00k0q4j.jpg)

这么强大的 NoSQL，缺点也是很致命的

缺点：

- 不支持 SQL 的标准语言
- 不支持 ACID
- 只能保证数据相对一致性

也就是说，你换一个 NoSQL，就需要重新学习它的使用，学习成本高了

而且不支持 ACID，这意味着如果在特定时间段内没有特定数据项的更新，则最终对其所有的访问都将返回最后更新的值

所以现在大多数企业都会采用 SQL + NoSQL 根据不场景组合使用的方案

## NewSQL

NewSQL是一种相对较新的形式，目标是将 SQL 的 ACID 保证与 NoSQL 的可扩展性和高性能相结合

听上去像是汲取了刚刚提到两个方向的长处，更像是一种完美的解决方案

虽然现在互联网上已经有一些 NewSQL 的产品，但是祺老弟认为要实现数据的强一致性又不影响性能的话，这条路还应该挺长

我们可以大胆猜测以后的 NewSQL，应该是具备海量数据处理能力，而且在分布式的基础上仍然具备事务能力，而且还能按照旧的 SQL 标准语言进行查询

![](http://pztl2fha9.bkt.clouddn.com/9150e4e5ly1fj7tat55yvj206o06o75h.jpg)

## 总结

不过技术的发展很难说准，想成为一个不被技术淘汰的程序猿，只能不断学习提升自己，跟着大厂的步伐走

祺老弟不敢说以后会不会淘汰传统的 SQL，会不会导致无数 DBA 失业，但是能确定的一点是，学就完事了

![](http://pztl2fha9.bkt.clouddn.com/006dMd5bgy1fl6gzclm1mj30j60j6gmp.jpg)

![](http://pztl2fha9.bkt.clouddn.com/0.png)