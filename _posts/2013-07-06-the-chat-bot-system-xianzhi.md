---
layout: post
title: "the chat bot system: XianZhi"
description: ""
category: 
tags: [chat bog, xianzhi, deepqa]
---
{% include JB/setup %}

### 系统构成:
&nbsp;&nbsp;整个大系统由逻辑系统和数据两部分构成。<br>

&nbsp;&nbsp;逻辑系统由三个子系统构成：mobile-end app, web logic processing system, chat-bot server system. 其中，chat-bot server比较复杂，再划分为四个子系统：chat-bot logic server system, searching server system, input智能提示子系统. <br>

&nbsp;&nbsp;数据系统中有一个在线系统和两个离线系统. 离线系统包括爬虫系统, 数据预处理系统, 而在线数据系统服务于广告主和内容生产商(注意这两个可以是同一个人)。


### 开发进度

1. **逻辑系统.**
- mobile-end app: 70%
- web logic processing system: 70%
- chat-bot logic server system: 70%
- searching server system: 80%
- input智能提示子系统: No

2. **数据系统.**
- 在线数据系统: No 
- 爬虫系统: 初级版本的爬虫已经上线。每天可以收获到15w有效数据items。
- 数据预处理系统: 60%

### 任务分工

&nbsp;&nbsp;除了mobile-end app是请一个研究生一年级的同学开发的(需要支付salary)，其余工作目前都是由andy feng完成。

<br>
<br>

