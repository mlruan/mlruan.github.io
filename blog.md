---
layout: default
title: "Blog"
permalink: /blog/
---


<ul>
  {% for post in site.posts %}
    {% unless post.categories contains "backpacking" %}
      <li>
        <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%b %d, %Y" }}
      </li>
    {% endunless %}
  {% endfor %}
</ul>
