---
title: 主页
layout: default
---
<ul>
  {% for post in site.posts %}
    <li>
      <a style="font-size:25px;" href="{{ post.url }}">{{ post.title }}</a>
      <p>{{ post.excerpt }}</p>
    </li>
  {% endfor %}
</ul>
