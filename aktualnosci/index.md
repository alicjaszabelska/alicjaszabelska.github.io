---
title: 'Aktualności'
layout: aktualnosci
---

<h3>{{ page.title }}</h3>
<ul class="aktualnosci">
  {% for post in site.posts %}
    <li><span>{{ post.date | date: "%m/%d/%y" }}</span> &raquo; <a href="{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>
