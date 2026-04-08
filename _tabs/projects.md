---
title: Projects
icon: fas fa-project-diagram
order: 3
---

## 💻 My Projects

{% for post in site.posts %}
  <div style="margin-bottom: 20px;">
    <h3>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </h3>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
