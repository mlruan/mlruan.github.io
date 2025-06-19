---
layout: default
title: "Backpacking"
permalink: /backpacking/
---



<ul>
  {% for post in site.categories.backpacking %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>
