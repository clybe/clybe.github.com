---
layout: page
title: 分享程序员生活的点点滴滴
tagline: 暂时只有Android了。。
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)


## 我的动态

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Skills

1. 解决gem install jekyll遇到如下错误的解决方法

ERROR:  Error installing jekyll:
liquid requires RubyGems version >= 1.3.7

使用 $ sudo gem update --system
参考 [http://stackoverflow.com/questions/4904786/how-do-you-install-jekyll-on-osx](http://stackoverflow.com/questions/4904786/how-do-you-install-jekyll-on-osx)


## 待学习
    
1. [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

2. Fork http://github.com/plusjade/jekyll-bootstrap to custom my theme

