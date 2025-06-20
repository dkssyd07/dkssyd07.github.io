---
layout: default
title: English Study
---

# ✏️ English Study

영어 공부 팁과 전략, 공부 기록을 공유하는 공간입니다.

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "english" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%Y-%m-%d" }})</li>
    {% endif %}
  {% endfor %}
</ul>
