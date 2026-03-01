---
layout: default
title: Home
---

<p style="text-align: center;">
  Github   • <a href="https://github.com/vitor-schipani">vitor-schipani</a><br>
  LinkedIn • <a href="https://www.linkedin.com/in/vitor-luiz-schipani">vitor-luiz-schipani</a><br>
  Email    • <a href="https://github.com/vitor-schipani">vitorschipani [at] outlook {dot} com</a>
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
