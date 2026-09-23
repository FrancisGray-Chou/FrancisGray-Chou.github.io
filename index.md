---
layout: default
title: Francis Gray Blog
---

Welcome to **Francis Gray's technical blog**.

Topics include:

- Algorithms
- Systems
- AI
- Programming notes
- Random thoughts

## 最新文章

<ul>
  {% for post in site.posts %}
    <li>
      <span>{{ post.date | date: "%Y-%m-%d" }}</span> &raquo; 
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
