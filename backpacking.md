---
layout: default
title: "Backpacking Life"
permalink: /backpacking/
---

# My Backpacking Adventures

<ul>
  {% for post in site.categories.backpacking %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
    </li>
  {% endfor %}
</ul>
