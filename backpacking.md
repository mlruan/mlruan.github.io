---
layout: default
title: "Backpacking"
permalink: /backpacking/
---

<ul style="list-style-type:none; padding-left:0;">
  {% for post in site.categories.backpacking %}
    <li style="margin-bottom: 2em;">
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
      <p>{{ post.excerpt | strip_html | truncate: 200 }}</p>
    </li>
  {% endfor %}
</ul>
