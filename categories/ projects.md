---
layout: default
title: IT Projects
---

# 💻 IT Projects

파이썬, 자동화, IoT 등 다양한 기술 프로젝트들을 이곳에 정리했습니다.

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "it-projects" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%Y-%m-%d" }})</li>
    {% endif %}
  {% endfor %}
</ul>
