---
layout: post
title: 提醒 190824 复合分享 Flutter+MiniBlink+APISIX
description: ~ 社区活动, 值得掺合;-)
author: zoomq
categories: Events
tags:  gdg event DevFest summary
---


上岛,上岛,上 -> 淇澳岛

在珠海也算是非常有名的去处了...

可是从来没有什么技术分享在岛上举行的吧?


其实不然, 从5年前, 就一直有各种小型技术分享在组织,

只是,这个月开始 极简汇率和 GDG珠海 联合, 准备长期组织公开技术分享, 
头一次就是三连击:

<!--more-->

## 活动:
- 报名: [Chromium\+APISIX GDG珠海 MeetUp](https://www.meetup.com/Zhuhai-GDG/events/263962960/)
- 时间: 190824 1313~1642
- 地点: 极简汇率
    + 珠海市香洲区南腾街5号 · Zhuhai
    + 交通换乘指引, 见报名页面尾部详细说明

## 内容:

Chromium 是 Chrom 的开源版本, 已经有很多厂商基于这一工程拓展开发专有浏览器器了, 但是, 有一位独行侠, 单枪匹马用两年时间,从 Chromium 几百万行代码中精密抽取出 blink 引擎,并加以优化, 得以作为独立模块, 提供给工程师嵌入到应用中, 获得比 Chrome 还要快的网页解析能力;
他怎么作到的?
为什么要干这事儿?
现在 mini-blink 可以怎么用?
以及如何通过 GN 自动化完成跨平台兼容编译的?


@龙泉寺扫地僧(weolar)

- 一个醉心于浏览器内核技术的老程序员;
- 一个受益于谷歌技术却"抗争"谷歌"霸权"的反抗者;
- 曾花费几年思考什么是最完美的界面框架,最终投身浏览器事业. 
- 七年磨一剑,打造了全世界最小巧浏览器内核. 
- Github热门开源项目Miniblink作者,热心于解惑浏览器内核知识. 

------

Nginx 是另外一座开源丰碑, 当前全球有超过一半网络流量是通过 Nginx 及其衍生产品发布的,
而 APISIX 则是将 Luajit 优雅嵌入到 Nginx 从而获得灵活的应用/接口/流量/...业务网关控制直接通过类似配置文件的 lua 脚本实现了,
甚至可以省去应用系统, 直接和后台数据库关联起来,完成核心业务的动态提供,
基于 Nginx 极其鲁棒的架构, 瞬间获得单机负载能力几十倍的提升...
而这种颠覆性作品, 仅仅由两位工程师完成,
那么 APISIX 到底还能作什么?
如何确保代码品质和复杂的系统兼容性?
以及如何完成开源技术商业化的?


@温铭@APISIX

- 开源微服务网关 APISIX 作者,
- 技术专栏"OpenResty 从入门到实战"作者,
- OpenResty 软件基金会创始人,前 360 开源技术委员会委员,
- 在互联网安全公司工作了 10 年,负责开发过云查杀,反钓鱼和企业安全产品. 
- 现在专注于 API 网关领域,让业务流量更加安全和快速的得到处理. 

------

当 Flutter 遇上 "好奇的猫"
剖离做为一位程序员的角度来解读 Flutter,这将会是一种什么体验呢?其实我也不知,但潜意识告诉我要用自己的方式来解读,至少我是有所收获,但更多的是想让身边的人有所收获. 
如果说要给这次分享打上一些关键词,我想更多的是:
语言,语法,体验,至于效果如何,也让我期待这一场未知的技术分享!


@张金泽
> 致力于 Android 五年有余,收获的是
一种认识世界的方式,为什么呢?
因为当是一个毛头小子时,千变万化的眼前
诸如一个个谜,是什么解答了这些谜?
与我的伙伴 Android 相处的点点滴滴!

> 担任于极简汇率 Android Leader,收获的是
一种展示自我的方式,为什么呢?
因为当是一个 Android Leader 时,千变万化的需求
与飞逝的时间的战争打响,是什么平息了这场战争?
与我的伙伴 Android 交谈的思想碰撞!


------

还有...
各种有用有趣有种的开源技术话题,
在 极简汇率的 Loft 空间的三小时,
我们可以聊任何有兴趣的话题 ...



## 预约:
~ 珠海GDG 是你的社区, 所以, 任何嗯哼都可以嗯哼

- 除了 以上主题 开发, 你还讨论/分享什么?
    + 希望从 GDG 进一步获得什么?
    + 渴望在 GDG 分享什么?
    + 期望学习什么开源技术?
- 请回复当前网页回答
    + 或是邮件给
    + zhgdg-organizing-volunteers@googlegroups.com


> NN 3747