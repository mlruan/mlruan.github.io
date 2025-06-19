---
layout: default
title: "Blog"
---

{% for post in site.posts %}
  {% unless post.categories contains "backpacking" %}
    <!-- Your post rendering logic here -->
  {% endunless %}
{% endfor %}

