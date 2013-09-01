---
layout: post
title: "The chat bot system: Xiaohuoban"
description: ""
category: 
tags: [chat bog, xianzhi, deepqa]
---
{% include JB/setup %}

### The system architecture:
&nbsp;&nbsp;The big system consists of a logic system and a data processing system. <br>

&nbsp;&nbsp;The logic system consists the following three subsystems: mobile-end app, web logic processing system, chat-bot server system. However, the chat-bot server is somehow complex, so it should be splited into the following four subsystems: chat-bot logic server system, searching server system, input suggestions system. More information can be found here [Equip Chatbot with knowledge-rich mind.doc](https://github.com/ideafold/ideafold.github.com/blob/master/assets/Equip%20Chatbot%20with%20knowledge-rich%20mind.doc?raw=true)<br>

&nbsp;&nbsp;Data processing system includes one online system and two offline systems. Crawler system and the data preprocess system belong to the offline systems, and the online system service the advertisers and content producers.


### Development milestores

1. **The logic system.**
- mobile-end app: 95% `(Beta version will be released in those days!!, please pay attention)`
- web logic processing system: 100%
- chat-bot logic server system: 100% (but data is under cleaning)
- searching server system: 100%
- input suggestions system: 100%

2. **The data processing system.**
- The online data collecting system: 0% 
- Crawler system: Beta version had been online
- Offline data preprocess system: 80%

### Team compostion

&nbsp;&nbsp;Andy Feng is main developer and investor, besides some optimizing work on mobile-end app was undertook by a grade one postgraduate classmate (needing to pay salary).

<br>
<br>

