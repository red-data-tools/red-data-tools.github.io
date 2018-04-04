---
title: Red Data Toolsブログ
---

# Red Data Toolsブログ

<ul class="posts">
  {% for post in site.posts limit: 10 %}
    {% if post.categories contains page.language %}
      <li class="post">
        <span class="date">{{ post.date | date: "%Y-%m-%d" }}</span>:
        <a href="{{ post.url}}" title="{{ post.title | escape }} ({{post.date | date: '%Y-%m-%d' }})">{{ post.title }}</a>
      </li>
    {% endif %}
  {% endfor %}
</ul>
