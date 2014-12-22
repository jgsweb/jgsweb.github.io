---
layout: page
title: Japanese Global Scholars
tagline:
---
{% include JB/setup %}

## Welcome to Our Blog!

### 概要
世界中の日本人学生が、各々の活動拠点で感じる各地域の特色・文化・社会を日本人学生ならではの視点からリポートします。

### コンテンツ

『長期間住んで、活動してみないと分からない海外現地のミクロでローカルな視点・情報をシェアし合おう！』そんな思いから集った有志の日本人学生が現地の特色・文化・社会をリポート。旅行、留学、ビジネス、交際、多くの局面で感じる世界各地の特徴を日本人学生の生の声で伝えます。

### Facebook

私達JGSは<span style="font-size:18pt"><a href="https://www.facebook.com/Japanese.Global.Scholars">Facebook</a></span> 上でも活動しています。
Please give us your heartful "Like" !! 




### Back Number
<ul class="posts">
  {% for post in site.posts %}
    <li style="font-size:14pt"><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

