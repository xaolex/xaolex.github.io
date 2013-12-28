---
layout: page
title: Hello World!
tagline: 世界是你的，世界也是我的。
---
{% include JB/setup %}

这个是网站首页，网站用了Jekyll（a blog-aware, static site generator in Ruby）假如你有兴趣的话可以到 [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)看看。

还用了Jekyll Bootstrap的主题，请看这里： [Jekyll Bootstrap](http://jekyllbootstrap.com)

    
## 文章发表

这里是博客发表的文章列表：

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>



