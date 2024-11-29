---
layout: grid_list
title: Projects
permalink: /projects/
---

# Projects

<div class="projects-grid">
  {% for post in site.posts %}
    <div class="project-item">
      <a href="{{ post.url }}">
        <h2>{{ post.title }}</h2>
        <p>{{ post.excerpt }}</p>
      </a>
    </div>
  {% endfor %}
</div>