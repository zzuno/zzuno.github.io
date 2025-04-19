---
permalink: /blog/
title: "Blog"
author_profile: true
layout: default
---

<span class='anchor' id='blog'></span>

# 📝 Blog Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>({{ post.date | date: "%Y-%m-%d" }})</small>
    </li>
  {% endfor %}
</ul>
