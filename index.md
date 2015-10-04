---
layout: page
title: 天行健，君子以自强不息；地势坤，君子以厚德载物
tagline: Supporting tagline
---
{% include JB/setup %}

知识需要文字来承载，此博客旨在于记录在学习研究生涯中遇到的一些问题及值得记录的经验。

## 个人简介

中国科学院在读博士一名，感兴趣内容为机器学习、生物医学工程、信号处理等。

## 博客目录

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## 联系方式

工作邮箱：yan.yan@siat.ac.cn

个人邮箱：yanyan.cas@gmail.com

我的 [GitHub主页面](http://github.com/yanyan-cas)

