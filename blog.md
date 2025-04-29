---
layout: default
title: Blog
permalink: /blog/
---

<ul class="post-list">
  {% for post in site.posts %}
    <li>
      <div class="post-item">
        <a class="post-link" href="{{ post.url }}">{{ post.title }}</a>
        <span class="post-date">{{ post.date | date: "%b %d, %Y" }}</span>
      </div>
    </li>
  {% endfor %}
</ul>
