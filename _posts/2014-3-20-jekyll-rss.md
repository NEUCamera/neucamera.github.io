---
layout: post
title:  "为 Jekyll blog增加rss功能"
date:   2014-03-20
categories: common
tags: jekyll
---

通过bing搜索，找到了一个jekyll的插件[agelber/jekyll-rss](https://github.com/agelber/jekyll-rss)。

使用起来非常简单：

1. 把[rssgenerator.rb](https://github.com/agelber/jekyll-rss/blob/master/rssgenerator.rb)复制到`_plugins`目录（如果没有就自己新建一个，与`_posts`等目录同级）里。
2. 修改`_config.yml`文件即可，修改方法参见[这里](https://github.com/agelber/jekyll-rss#usage)。

<a href="/rss.xml"> rss.xml </a>