# GolangStudy: Golang 面试学习

[在线阅读](https://cnymw.github.io/GolangStudy)

本项目旨在指导程序员们如何从基础开始系统的学习 Go 语言，并学习面试所需知识点。

Go 是一门非常容易上手的语言，语法简洁，代码易读，如果你有常用语言的基础，那看一本[Go 语言圣经](https://docs.hacknode.org/gopl-zh/index.html)后便可上手开发业务代码。

但是，想通过 Go 语言的面试可能需要更加系统，全面的知识，本项目通过知识点的总结来提升面试通过的几率。

本项目不是博客，一个问题不会讲的特别细致，如果想要更加深入的了解某个知识点的话，建议使用搜索引擎去搜索经典博客加深理解，项目中也会推荐一些好的文章供参考。

本项目更加看重的是对于知识点系统的一个总结，能够通过一句话，一张思维导图来把一类知识进行讲解，这样在面试前把所有的思维导图都过一遍就能更大的提升面试通过的几率了，平时空余的时候拿出思维导图进行复习也能加深理解。

## Golang 学习路线图（TODO）

<img src="https://cnymw.github.io/GolangStudy/docs/img/首页-Golang路线图.png" width="50%" alt="nil"/>

## go

- [Go 基础](/docs/go-基础/go-基础.md)
- [Go 并发(TODO)](/docs/go-并发.md)
- [Go 接口(TODO)](/docs/go-接口.md)
- [Go 检测竞态条件](/docs/go-检测竞态条件.md)
- [Go 性能分析：pprof实战](https://blog.wolfogre.com/posts/go-ppof-practice/)
- golang机制
  - [Go 调度](/docs/go-调度.md)
  - [Go 垃圾回收](/docs/go-垃圾回收.md)
- golang sdk
  - [Go 源码 SDK 目录](https://cloud.tencent.com/developer/doc/1101)
  - [Go 源码解读 标识符](/docs/go-源码解读-标识符.md)
  - [Go 源码解读 双向链表 list](/docs/go-源码解读-双向链表list.md)
  - [Go 源码解读 程序分析pprof(TODO)](/docs/go-源码解读-程序分析pprof.md)
  - [Go 源码解读 同步模块sync mutex(TODO)](/docs/go-源码解读-同步sync-mutex.md)
  - [Go 源码解读 同步模块sync once(TODO)](/docs/go-源码解读-同步sync-once.md)
- zap
  - [Go 源码解读 高性能日志库 zap(TODO)](/docs/go-zap.md)
- grpool
  - [Go 源码解读 轻量级线程池 grpool(TODO)](/docs/go-grpool.md)
- 面试题
  - [Go 有几种连接字符串的方法?](/docs/go-面试题-连接字符串方法.md)

---

## Kubernetes

- [kubernetes.io 官方文档](https://kubernetes.io/zh-cn/)
  - [Kubernetes 概述｜视频学习｜完整版](/docs/Kubernetes-概述/Kubernetes-概述.md)
  - [Kubernetes 组件｜视频学习｜完整版](/docs/Kubernetes-组件/Kubernetes-组件.md)
  - [Kubernetes 理解对象｜视频学习｜完整版](/docs/Kubernetes-理解对象/Kubernetes-理解对象.md)
  - [Kubernetes namespace｜视频学习｜完整版](/docs/Kubernetes-namespace/Kubernetes-namespace.md)
  - [Kubernetes 标签｜视频学习｜完整版](/docs/Kubernetes-标签/Kubernetes-标签.md)
  - [Kubernetes 节点｜视频学习｜完整版](/docs/Kubernetes-节点/Kubernetes-节点.md)
- [Kubernetes 基本概念和术语](/docs/Kubernetes-基本概念和术语.md)
- [Kubernetes kubectl命令(TODO)](/docs/Kubernetes-kubectl命令.md)
- [Kubernetes 中文手册](https://www.kubernetes.org.cn/docs)

---

## 数据结构

- [线性表](/docs/数据结构-线性表.md)
  - [栈](/docs/数据结构-栈.md)
  - [顺序表](/docs/数据结构-顺序表.md)
  - [链表](/docs/数据结构-链表.md)
  - [队列](/docs/数据结构-队列.md)
- 树
  - [二叉树](/docs/数据结构-二叉树.md)
  - [二叉搜索树(TODO)](/docs/数据结构-二叉搜索树.md)
- [哈希表](/docs/数据结构-哈希表.md)
- 面试题
  - [B树和B+树之间的区别](/docs/数据结构-面试题-B树和B+树的区别.md)

---

## 算法

- [排序算法总结](/docs/算法-排序算法.md)
  - [插入排序](/docs/算法-插入排序.md)
  - [堆排序](/docs/算法-堆排序.md)
  - [归并排序](/docs/算法-归并排序.md)
  - [快速排序](/docs/算法-快速排序.md)
- [动态规划](/docs/算法-动态规划.md)
- [前中后缀表达式](/docs/算法-前中后缀表达式.md)
- [滑动窗口(TODO)](/docs/算法-滑动窗口.md)
- [二分查找(TODO)](/docs/算法-二分查找.md)
- [分布式id生成算法：雪花算法](/docs/算法-雪花算法.md)

---

## 数据库

- [mysql InnoDB 体系结构](/docs/数据库-mysql-InnoDB体系结构.md)
  - [mysql InnoDB 内存结构(TODO)](/docs/数据库-mysql-InnoDB内存结构.md)
  - [mysql InnoDB 磁盘结构(TODO)](/docs/数据库-mysql-InnoDB磁盘结构.md)
- [mysql InnoDB 主从复制(TODO)](/docs/数据库-mysql-InnoDB主从复制.md)
- mysql InnoDB 索引
  - [mysql InnoDB 聚集索引和辅助索引](/docs/数据库-mysql-InnoDB聚集索引和辅助索引.md)
- InnoDB 锁和事务模型
  - [mysql InnoDB 多版本控制（TODO）](/docs/数据库-mysql-InnoDB多版本控制.md)
  - [mysql InnoDB 锁机制](/docs/数据库-mysql-Innodb锁机制.md)
  - [mysql InnoDB 事务隔离级别(TODO)](/docs/数据库-mysql-InnoDB事务隔离级别.md)
  - [mysql InnoDB 锁定读(TODO)](/docs/数据库-mysql-InnoDB锁定读.md)
  - [mysql InnoDB 死锁](/docs/数据库-mysql-死锁.md)
  - [mysql InnoDB 死锁案例](https://github.com/aneasystone/mysql-deadlocks)
- Mysql常用工具
  - [mysql 慢查询分析工具 mysqldumpslow](/docs/数据库-mysql-慢查询分析工具mysqldumpslow.md)
  - [mysql 压测工具 mysqlslap](/docs/数据库-mysql-压测工具mysqlslap.md)

---

## 设计模式

- [策略模式](/docs/设计模式-策略模式.md)
- [观察者模式](/docs/设计模式-观察者模式.md)
- [装饰器模式](/docs/设计模式-装饰器模式.md)

---

## Docker
- [Docker — 从入门到实践](https://vuepress.mirror.docker-practice.com)
- [Docker 基础(TODO)](/docs/docker-docker基础.md)

---

## redis

- [redis 键命令](/docs/redis-键命令.md)
- [redis 字符串命令](/docs/redis-字符串命令.md)
- [redis 哈希表命令](/docs/redis-哈希表命令.md)
- [redis 列表命令](/docs/redis-列表命令.md)
- [redis 集合命令](/docs/redis-集合命令.md)
- [redis 有序集合命令](/docs/redis-有序集合命令.md)
- [redis Hyperloglog命令](/docs/redis-Hyperloglog命令.md)
- [redis 发布订阅命令](/docs/redis-发布订阅命令.md)
- [redis 复制命令](/docs/redis-复制命令.md)
- [redis 数据库命令](/docs/redis-数据库命令.md)
- [redis 事务命令](/docs/redis-事务命令.md)
- [redis 持久化命令](/docs/redis-持久化命令.md)
- [redis 配置选项命令](/docs/redis-配置选项命令.md)
- [redis 调试命令](/docs/redis-调试命令.md)
- [redis 内部命令](/docs/redis-内部命令.md)
- [redis 持久化（TODO）](/docs/redis-持久化.md)
- [redis sentinel（TODO）](/docs/redis-sentinel.md)
- [redis 集群（TODO）](/docs/redis-集群.md)
- [redis 实现分布式锁](/docs/redis-实现分布式锁.md)
- 面试题
  - [redis 有什么作用](/docs/redis-面试题-redis有什么作用.md)
  - [redis 是单线程但为什么执行速度这么快](/docs/redis-面试题-redis为什么这么快.md)

---

## elasticsearch

- [Elasticsearch](/docs/Elasticsearch-概览.md)
- [Elasticsearch: 权威指南](https://www.elastic.co/guide/cn/elasticsearch/guide/current/index.html)

---

## 消息中间件

- [kafka 介绍(TODO)](/docs/消息中间件-kafka-介绍.md)
- 面试题
  - [kafka 为什么会丢消息?](/docs/消息中间件-面试题-kafka为什么丢消息.md)

--- 

## 操作系统

- [Linux 命令大全](https://man.linuxde.net)
- [Linux 教程](https://www.runoob.com/linux/linux-tutorial.html)
- [Linux 文件操作](/docs/linux-文件操作.md)
- [Linux inode详解](https://www.cnblogs.com/llife/p/11470668.html)
- [Linux 监测系统](/docs/linux-监测系统.md)
- [Linux 抓包工具tcpdump详解](/docs/linux-抓包命令tcpdump.md)
- [Linux tcpdump命令详解(转)](https://www.cnblogs.com/ggjucheng/archive/2012/01/14/2322659.html)
- [Linux tcp分析命令ss详解](/docs/linux-tcp分析命令ss.md)
- [Linux curl命令详解](/docs/linux-curl命令.md)
- [Linux namespaces 命名空间](/docs/linux-namespaces.md)
- 面试题
  - [进程和线程，协程的区别(TODO)](/docs/操作系统-面试题-进程线程协程的区别.md)
- 专业博客
  - [redhat sysadmin](https://www.redhat.com/sysadmin/)

---

## 网络

- [TCP-IP 详解：链路层](/docs/网络-TCP-IP详解-链路层.md)
- [TCP-IP 详解：IP 网际协议](/docs/网络-TCP-IP详解-IP.md)
- [TCP-IP 详解：ARP 地址解析协议](/docs/网络-TCP-IP详解-ARP.md)
- [TCP-IP 详解：RARP 逆地址解析协议](/docs/网络-TCP-IP详解-RARP.md)
- [TCP-IP 详解：ICMP Internet控制报文协议](/docs/网络-TCP-IP详解-ICMP.md)
- [TCP-IP 详解：TCP 传输控制协议（TODO）](/docs/网络-TCP-IP详解-TCP传输控制协议.md)
- [grpc：grpc简介(TODO)](/docs/网络-grpc简介.md)
- 面试题
  - [HTTP 1.0、1.1、2.0、3.0 区别(TODO)](/docs/网络-http-http版本区别.md)

---

## 分布式

- [分布式：分布式架构](/docs/分布式-分布式架构.md)
- [分布式：一致性协议(TODO)](/docs/分布式-一致性协议.md)
- [分布式：断路器模式(TODO)](/docs/分布式-断路器模式.md)
- [分布式：etcdctl 基本使用](/docs/分布式-etcd-etcdctl基本使用.md)
- [分布式：理解 etcd](https://zhuanlan.zhihu.com/p/96721097)
- [分布式：service mesh 入门(TODO)](/docs/分布式-servicemesh-servicemesh入门.md)

---

## leetcode

- 链表
  - [leetcode-2-两数相加](/docs/leetcode-2-两数相加.md)
  - [leetcode-21-合并两个有序链表](/docs/leetcode-21-合并两个有序链表.md)
  - [leetcode-61-旋转链表](/docs/leetcode-61-旋转链表.md)
- 哈希表
  - [leetcode-1-两数之和](/docs/leetcode-1-两数之和.md)
  - [leetcode-3-无重复字符的最长子串](/docs/leetcode-3-无重复字符的最长子串.md)
  - [leetcode-30-串联所有单词的子串](/docs/leetcode-30-串联所有单词的子串.md)
  - [leetcode-242-有效的字母异位词](/docs/leetcode-242-有效的字母异位词.md)
  - [leetcode-349-两个数组的交集](/docs/leetcode-349-两个数组的交集.md)
  - [leetcode-350-两个数组的交集2](/docs/leetcode-350-两个数组的交集2.md)
- 动态规划
  - [leetcode-5-最长回文子串](/docs/leetcode-5-最长回文子串.md)
  - [leetcode-53-最大子序和](/docs/leetcode-53-最大子序和.md)
  - [leetcode-64-最小路径和](/docs/leetcode-64-最小路径和.md)
  - [leetcode-70-爬楼梯](/docs/leetcode-70-爬楼梯.md)
  - [leetcode-115-不同的子序列](/docs/leetcode-115-不同的子序列.md)
- 树
  - [leetcode-100-相同的树](/docs/leetcode-100-相同的树.md)
  - [leetcode-1038-从二叉搜索树到更大和树](/docs/leetcode-1038-从二叉搜索树到更大和树.md)
- 栈
  - [leetcode-150-逆波兰表达式求值](/docs/leetcode-150-逆波兰表达式求值.md)
  - [leetcode-224-基本计算器](/docs/leetcode-224-基本计算器.md)
  - [leetcode-225-用队列实现栈](/docs/leetcode-225-用队列实现栈.md)
- [leetcode-15-三数之和](/docs/leetcode-15-三数之和.md)
- [leetcode-27-移除元素](/docs/leetcode-27-移除元素.md)
- [leetcode-56-合并区间](/docs/leetcode-56-合并区间.md)
- [leetcode-164-最大间距](/docs/leetcode-164-最大间距.md)
- [leetcode-922-按奇偶排序数组2](/docs/leetcode-922-按奇偶排序数组2.md)
- [leetcode-976-三角形的最大周长](/docs/leetcode-976-三角形的最大周长.md)

---

# 参考资料
- [麻省理工学院公开课：算法导论](http://open.163.com/special/opencourse/algorithms.html)
- [LeetCode All in One 题目讲解汇总](https://github.com/grandyang/leetcode)
- [kafka教程](https://www.orchome.com/kafka/index)
