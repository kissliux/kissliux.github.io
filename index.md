---
layout: page
title: Hello World!
tagline: Supporting tagline
---
{% include JB/setup %}

## hello 我是刘兴，
原谅我一生放荡不羁的笑点
![lf]("assets/images/lf.png");

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>




