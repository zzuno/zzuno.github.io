---
layout: default
title: "Blog"
permalink: /blog/
author_profile: true
---

# 📝 Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
