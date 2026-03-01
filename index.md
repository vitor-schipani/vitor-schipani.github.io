---
layout: default
title: Home
---

<p style="text-align: center;">
  <a href="https://github.com/vitor-schipani">GitHub</a> | vitorschipani [at] outlook {dot} com
</p>

## Posts

<ul>
  {% for post in site.posts %}
  <li>
    <a href="{{ post.url }}">{{ post.title }}</a>
    <span> — {{ post.date | date: "%B %d, %Y" }}</span>
  </li>
  {% endfor %}
</ul>
