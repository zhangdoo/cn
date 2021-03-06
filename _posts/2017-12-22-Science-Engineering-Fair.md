---
published: true
layout: post
title: "中小学生科技竞赛"
author: Yu
categories: 所思所悟
tags:
- 竞赛
- 教育
---

首先要吐槽一个事情：最近在指导一个高二的中学生独立做癌症相关的科学研究，她要参加一个重要的科技竞赛，首先需要在州内参加比赛，如果做得好，她可以被选上参加全国比赛。
说是指导，其实就是我替她写所有的程序（R语言），这个研究里包含两种癌症的数据，我写完程序，她用一组数据跑一遍确定程序能运行，然后换一组数据再跑一遍（她会把程序文件复制一份，改数据路径和变量名字，就是自己写的程序了 <code>-_-</code>）。课题做了将近两个月，来实验室不到8次。她对写程序一点都没学会，连安装软件包不提醒的话都不知道如何安装，记得来实验室的第一天，就告诉她要自己主动学习一下编程，想必给她的自学材料也一点没看过。从不问我问题，我问她懂不懂，她都说懂。我还发现她连excel里自动填充功能都不会用。

根据同她平时聊天以及她做课题的表现，这位同学应该是一个非常聪明的学生，但是她并不一定能完成这个课题，我觉得这个课题已经超出她的能力范畴了。美国的中学教育其实比国内的中学教育让学生觉得更加辛苦，不仅要学习成绩好，体育运动好，参加各类社会志愿活动，还要有时间做科学研究参加竞赛。这不是只比拼一次高考成绩，而是各种活动都如同高考那么重要。这个高中生曾说过，如果要坚持体育运动，就要牺牲自己睡眠时间。但是这种科技竞赛，如果是几个学生一组来完成一个课题，我觉得整个科研过程和结果都比较可信。若是单个学生独立完成科研，能做到的人其实是凤毛麟角。然而每年参加这种个人科研比赛的高中生还是满多的，这其中的工作很多都是家长或者大学里头的研究人员替他们做的。这种在评审时一眼就能看出来造假，让自己变成比赛分母的事情，当初何必浪费时间去做呢。究其原因，因为这个经历可以写在自己的简历上，为申请大学做准备。

不光美国的科技竞赛如此，国内的科技竞赛也有这样的现象，据我所知，我所还出现过小学生来做科研实习的事情，小学生来中科院打酱油，这不是扯么。通过这次经历，让我感慨万分，以后再看到什么中小学生发明了什么什么，科研做了什么什么，心里都要打个问号，如果是个人比赛的结果，基本都不会那么相信。

此外我还想说比赛获奖，有时靠得也不是个人能力，而是家长的能力，靠大树好乘凉。国内校级，区级的比赛，有关系就能脱颖而出，这种事情已经见怪不怪了。就连可以来大学和科研院所做科研，也应该是靠父母的关系。就我上面所说的两个学生例子，美国学生家长父母都是医生（精英移民的标配），网上还能找到关于他们的个人采访，这个学生做个志愿者取得了什么成绩都会上本地的新闻（为了申请大学铺路），新闻中还说她是同龄人中的领导者；那个小学生，父母也都是在研究所工作的。

综上所述，穷人家的孩子做到阶级向上越迁，真的很难，输在起跑线。

=================

2017.12.25 更新

知识分子上登载了一篇文章《清华，北大，人大资助招生选拔出更优秀的学生了吗》，结论是获得自主招生加分破格录取的学生通常是那些来自城市，父母受过大学教育，就读重点中学的优势阶层学生。这项研究说明了两个问题，家庭背景好的学生更可能获得自主招生加分。而因自主招生进入名校的学生们无论在学业表现、社会活动能力、非认知能力，还是就业去向上，都和普通高考统招生没有明显差异。

==================

2018.01.22 更新

介绍个科技竞赛作品。

https://www.dnaloopr.org/

不得不说题目起得真好《DNALoopR: A Novel High-Performance Machine Learning Predictor to Identify Genome-Wide 3D DNA Interactions in Cancer》，这就是一篇标准的生物信息工具类论文的题目啊。再看网站，非常专业的购买了SSL保护，上面一大堆媒体报道。结果要使用软件时，需要登录，竟然不是开源的。登录后再看软件，就一个输入，上传一个ChIP-seq文件，填写email地址，然后网站在计算完之后会将结果发给上传文件的人，连个样例都没有。。可惜手边没有ChIP-seq数据，否则还可以上传个文件测试一下。这个同学成功被斯坦福录取，并有机会出席了去年的诺贝尔颁奖典礼。

![DNALoopR](https://i.imgur.com/qo97F7f.png)

从外观上说，该网站的工程量已经很大了，可惜我无法对这个项目的软件和算法进行评价。高中时期的我，肯定做不出来这么牛X的项目。。。



