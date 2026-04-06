---
layout: default
title: Life
permalink: /life/
---

# Life

This is where I record daily life and thoughts.

## Posts

{% for post in site.posts %}
- [{{ post.title }}]({{ post.url }}) — {{ post.date | date: "%Y-%m-%d" }}
{% endfor %}
