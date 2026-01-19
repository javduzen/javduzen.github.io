---
layout: home
title: "Javduzen Daily"
---

Welcome to Javduzen Daily — short posts and updates.

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a> — <small>{{ post.date | date: "%B %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>