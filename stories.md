---
title: stories
layout: default
---

  {% for post in site.posts %}
 <a href="{{ post.url }}" >
      <img src="{{ post.image }}" alt="{{ post.title }}" width="200px">
  </a>
  {% endfor %}


