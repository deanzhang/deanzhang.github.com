---
layout: page
title: 你好程小木_!
tagline: 哈哈……
---
{% include JB/setup %}

## 简介

您好，欢迎您来到章与程的Blog世界。这里是我们的小世界。新浪微博请分别[@{{ site.author.sina_weibo1 }}]({{ site.author.sina_weibo_url1 }}) 和 [@{{ site.author.sina_weibo2 }}]({{ site.author.sina_weibo_url2 }})
<!-- 将此标记放在您希望呈现 +1 按钮的位置 -->
<g:plusone annotation="inline"></g:plusone>

Read [Jekyll Quick Start](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)

Complete usage and documentation available at: [Jekyll Bootstrap](http://jekyllbootstrap.com)

## Sample Posts

This blog contains sample posts which help stage pages and blog data.
When you don't need the samples anymore just delete the `_posts/core-samples` folder.

    $ rm -rf _posts/core-samples

Here's a sample "posts list".

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## To-Do

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.
