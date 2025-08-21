---
layout: default
title: Dev Log
---

# 🛠️ Dev Log

Here’s what I’ve been working on:

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a> — {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
