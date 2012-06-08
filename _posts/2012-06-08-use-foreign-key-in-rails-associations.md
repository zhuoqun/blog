---
layout: post
title: "[Rails] 使用 foreign_key 遇到 'XXX expected, got String' 的解决办法"
description: "Use foreign key in Rails associations"
category: 
tags: []
---
{% include JB/setup %}

久仰 [Ruby on Rails](http://rubyonrails.org/) 大名，最近终于有机会可以学习，并开始做一些小的东西练手。使用之后深深觉得 ror 名不虚传，极大地提高了 Web 开发的生产效率，不仅框架本身做得很好，还有许多非常优秀的 gem 可以使用，甚至在国际化（ I18n ）方面都有人帮助把所有日期和错误提示翻译好了，你只需要抓取需要的语言文件放到相应文件夹下即可。 ror 的文档非常多，这里我就不多做介绍了，只说一个最近碰到的小问题。这个问题虽然很小，但着实让我头疼了一阵子，搜索了好多资料都没有找到答案，最后还是靠自己慢慢尝试并解决了，所以分享一下解决方案。

###问题描述
