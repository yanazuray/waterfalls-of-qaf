---
layout: default
title: Blog
permalink: /blog/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <h3 class="post-title">
        <a href="{{ post.url }}">{{ post.title }}</a>
        <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      </h3>
    </li>
  {% endfor %}
</ul>
