---
layout: post
title:  "为Jekyll blog增加rss功能"
date:   2014-03-20
categories: common
tags: jekyll
---

2014-3-21更新

使用jekyll-rss在本地运行能够生成`rss.xml`，但是在github上无法生成，可能是插件没有配置明白。

换了一个rss生成方法，使用[jekyll-rss-feed](https://github.com/snaptortoise/jekyll-rss-feeds)。经过验证好用，直接将需要的`*.xml`复制到根目录下就可以。

----
通过bing搜索，找到了一个jekyll的插件[agelber/jekyll-rss](https://github.com/agelber/jekyll-rss)。

使用起来非常简单：

1. 把[rssgenerator.rb](https://github.com/agelber/jekyll-rss/blob/master/rssgenerator.rb)复制到`_plugins`目录（如果没有就自己新建一个，与`_posts`等目录同级）里。
2. 修改`_config.yml`文件即可，修改方法参见[这里](https://github.com/agelber/jekyll-rss#usage)。

<a href="/feed.xml">feed.xml </a>
