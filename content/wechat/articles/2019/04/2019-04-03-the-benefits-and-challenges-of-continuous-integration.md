---
title: "持续集成的收益与挑战"
description: "本文介绍了持续集成的定义，并解释了实施CI的各种收益与挑战"
date: 2019-04-03
tags:
- continuous integration
- ci
author: Jeffrey Lee
translator: donhui
original: https://dzone.com/articles/the-benefits-and-the-drawbacks-of-continuous-integ
---

毫无疑问，持续集成（ CI ）已成为一个软件开发的主流原则。CI 的收益在业界众所周知的，并且很难找到反对实施它的人。

在这里，我想把那些收益收集起来放到一个中心化的地方。但是我认为扮演反面角色并试图找出持续集成的弊端或挑战也是很有趣的。

## 什么是持续集成？
从根本上说， 持续集成（ CI ）是一种开发实践，开发人员每天都要将代码集成到共享的仓库中。在该仓库中，代码被自动构建进行验证用来在这个流程中检验尽早的发现任何问题。这允许团队花更少的时间回溯，而花更多的时间构建新特性。

## 持续集成的收益

### 1、缓解风险
据 [Martin Fowler ](https://martinfowler.com/articles/continuousIntegration.html)说，持续集成的最大收益是减轻风险。由于延迟了代码集成，团队将不断增加合并冲突的数量和严重性。当团队频繁集成（使用自动构建），他们减轻了潜在风险的数量，因为他们总是知道系统的当前状态。

### 2、质量保证
实施持续集成的团队对他们的操作更有信心。他们知道自动构建会立即捕获缺陷，这使他们能够保证质量。 他们也不会猜测系统中 bug 的数量，这允许他们能够向队友提供准确的数量，并为客户提供更好的服务。

### 3、提高可见性和加强团队合作
自动构建为团队提供了对其系统的完全可见性。他们知道问题的数量，并能快速的解决问题。提高可见性可以让团队有机会在小问题变成大之前通过协作解决。

## 持续集成的挑战

### 1、组织文化变革
一些企业更喜欢传统的方法，并且可能很难实施持续集成。 他们必须对员工进行再培训，这就意味着要对现有的业务进行大修。管理者可能会抵制因为持续集成并不能帮助他们实现公司的直接目标（例如：金钱在质量之上）。

### 2、难以维护
构建一个自动化的代码仓库不是一个简单的任务。 团队必须构建适当的测试套件，并花时间编写测试用例，而不是开发代码。 起初，这可能会让他们放慢速度，让他们对按时完成自己的项目失去信心。如果测试套件不稳定，它可能在某些天内完美地工作，但其他天可能不起作用。 然后团队将不得不花费更多的时间来弄清楚发生了什么。

### 3、大量的错误信息
对于较大的开发团队，他们可能每天都会看到 CI 错误消息，并开始忽略它们，因为它们还有其他任务和关注点。 他们可能会开始将一个破坏的构建视为一个正常的事情，并且缺陷可能开始堆积在一起。
