---
title: Projects
icon: fas fa-project-diagram
order: 3
---

## 💻 My Projects

{% for post in site.posts %}
  {% if post.title contains "Dashboard" or post.title contains "Project" %}
    <h3><a href="{{ post.url }}">{{ post.title }}</a></h3>
  {% endif %}
{% endfor %}
