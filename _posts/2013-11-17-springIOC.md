---
layout: post
title: SpringIOC
categories: Spring
date:   2013-11-17 13:31:01 +0800

---

* content
{:toc}


##### [编辑](https://github.com/ChangMike/blogs/edit/master/_posts/2013-11-17-springIOC.md){:target="_blank"}
------------------------
- 思想    
&emsp;Spring IOC，即控制反转，借鉴了工厂模式的思想。    
&emsp;依赖倒置原则要求依赖抽象不要依赖具体；但在一个类里要创建一个对象时，new 关键字后面一定要依赖一个具体的实现类。   
&emsp;这时，我们把创建对象的语句封装出来，封装到工厂类里是工厂模式，封装到配置文件是就是Spring的做法。
- 实现   
&emsp;参考代码[https://github.com/ChangMike/SpringIOC-test](https://github.com/ChangMike/SpringIOC-test){:target="_blank"}
