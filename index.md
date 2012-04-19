---
layout: page
title: Simple Examples
tagline: 
---
{% include JB/setup %}

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)


## 我的动态

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


## 待学习
    
1. [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

2. Fork http://github.com/plusjade/jekyll-bootstrap to custom my theme

