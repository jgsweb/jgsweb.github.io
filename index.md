---
layout: page
title: Japanese Global Scholars
tagline:
---
{% include JB/setup %}

### Welcome to Japanese Global Scholars' Blog!

### 概要
これは世界中の日本人学生たちの現地事情を発信していくページです。

### コンテンツ

TBA.




<ul class="posts">
  {% for post in site.posts %}
    <li style="font-size:14pt"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

