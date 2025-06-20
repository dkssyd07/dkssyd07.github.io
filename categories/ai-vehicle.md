---
layout: default
title: Autonomous Driving
---

# 🚗 AI-Based Autonomous Driving

딥러닝 기반 자율주행 자동차 실험과 관련된 글들을 모았습니다.

<ul>
  {% for post in site.posts %}
    {% if post.categories contains "autonomous" %}
      <li><a href="{{ post.url }}">{{ post.title }}</a> ({{ post.date | date: "%Y-%m-%d" }})</li>
    {% endif %}
  {% endfor %}
</ul>
