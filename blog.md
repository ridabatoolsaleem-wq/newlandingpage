---
layout: page
title: Blog
permalink: /blog/
---

# My Academic Journey

This section contains blog posts based on my semester journey, learning experiences, academic struggles, projects, and personal growth in Computer Engineering.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
      - {{ post.date | date: "%B %d, %Y" }}
    </li>
  {% endfor %}
</ul>
