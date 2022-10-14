---
title: GolangStudy
date: 2022-10-11
toc: false
---

本项目旨在指导程序员们如何从基础开始系统的学习 Golang 语言，并学习面试所需知识点。

Golang 是一门非常容易上手的语言，语法简洁，代码易读，如果你有常用语言的基础，那看一本 [Golang 语言圣经](https://docs.hacknode.org/gopl-zh/index.html) 后便可上手开发业务代码。

但是，想通过 Golang 语言的面试可能需要更加系统，全面的知识，本项目通过知识点的总结来提升面试通过的几率。

本项目不是博客，一个问题不会讲的特别细致，如果想要更加深入的了解某个知识点的话，建议使用搜索引擎去搜索经典博客加深理解，项目中也会推荐一些好的文章供参考。

本项目更加看重的是对于知识点系统的一个总结，能够通过一句话，一张思维导图来把一类知识进行讲解，这样在面试前把所有的思维导图都过一遍就能更大的提升面试通过的几率了，平时空余的时候拿出思维导图进行复习也能加深理解。

## Golang 学习路线

```markmap
- Golang 学习路线
  - 学习 Golang
    - 基础
    - 高级机制
    - 源码解读
    - 常用框架
  - Kubernetes
```

### 学习 Golang

Golang 语言的学习可以分为以下方向：

- 基础：开发核心能力
- 高级机制：线程调度，垃圾回收等，进阶的面试经常会考
- 源码解读：对 Golang 加深理解，进阶开发有帮助，面试不常考
- 常用框架学习：对生产开发有帮助，可以简单了解下，在技术选型的时候可以快速做出判断

### Kubernetes

Golang 常用在微服务，分布式场景，不经常用于较大的业务场景中。

常见的如开发一个微服务，部署到阿里/腾讯/华为云中，或者云原生自建的 Kubernetes 里，这个时候就需要学习并精通 Kubernetes 相关的知识。

很多企业在自建云，或者做云原生的转型，部署服务会逐渐的使用 Kubernetes，而放弃之前的物理机，虚拟机部署模式。所以面试的时候问到 Kubernetes 是比较常见的。

学习目录如下：

- [Kubernetes 概述](https://golang-study.netlify.app/kubernetes/kubernetes-概述/)
- [Kubernetes 组件](https://golang-study.netlify.app/kubernetes/kubernetes-组件/)
- [Kubernetes namespace](https://golang-study.netlify.app/kubernetes/kubernetes-namespace/)
