### LessOrMore

#### 致谢
---
+ 感谢[Less官网](http://lesscss.cn/)的样式，本Jekyll框架的样式都是基于Less官网的样式直接拷贝过来的。只是重构了JS，并且加入了Jekyll语法而已。
+ 感谢[Jekyll](https://jekyllrb.com/)团队做出如此优秀的产品
+ 感谢[Solar](https://github.com/mattvh/solar-theme-jekyll)的原作者[Matt Harzewski](http://www.webmaster-source.com/)，我的博客选用了此样式模版

#### 下载
---

使用git从[LessOrMore](https://github.com/luoyan35714/LessOrMore.git)主页下载项目

#### 配置
---

1. 只需配置`_config.yml`
2. 特别注意`baseurl`，该项不配置，会导致JS,CSS等静态资源错误

```
name: 博客名称
email: 邮箱地址
author: 作者名
baseurl: 项目名
github: github地址
# 需到百度统计官网(https://tongji.baidu.com/)申请自己的网站ID并在此处替换
baidu_analysis: 94be4b0f9fc5d94cc0d0415ea6761ae9
# 需到revolvermaps(http://www.revolvermaps.com/?target=setupgl)申请自己的网站ID并在此处替换
revolvermaps: 5ytn1ssq6za
```

#### 关于统计
---

本项目支持三种统计，分别是

+ [百度统计](https://tongji.baidu.com)

百度统计是后台统计，页面没有任何展示，可以登录百度统计查看详细的访问记录。
当Fork本项目之后需要去百度统计官网申请自己的baidu统计ID替换 `_config.yml` 文件中的 `baidu_analysis`。

+ [revolvermaps地图统计](http://www.revolvermaps.com/)

地图统计是展示在左侧边栏的地球，具体展示形式可以去官网定制。
当Fork本项目之后需要去revolvermaps地图官网申请自己的统计ID， 替换`_config.yml` 文件中的 `revolvermaps`。

+ [不蒜子统计](http://busuanzi.ibruce.info/)

不蒜子统计是出现在页面右上角的`本站总访问量n次`，它会自动识别客户所对应的域名，根据不同域名统计，所以并不需要Fork本项目者做任何修改。


#### 写文章
---

1. 在`/_posts`目录下新建一个文件，也可以创建文件夹并在文件夹中添加文件，方便维护。
2. 在文件中粘贴如下信息，并修改以下的`titile`,`date`,`categories`,`tag`相关信息，添加`* content {:toc}`为目录相关信息，在进行正文书写前需要在目录和正文之间输入至少2行空行。然后按照正常的Markdown语法书写正文。

``` bash
---
layout: post
title:  标题
date:   2016-08-27 01:08:00 +0800
#大类配置
categories: document
#小类配置
tag: 教程
---

* content
{:toc}


正文...
```

#### 执行
------------------------------------

``` bash
jekyll server
```

#### 效果
------------------------------------
打开浏览器并输入URL`http://localhost:4000/`,回车。
