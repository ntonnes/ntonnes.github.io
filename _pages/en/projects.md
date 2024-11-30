---
layout: grid_list
title: Projects
permalink: /en/projects/
lang: en
---

<div class="project-item">
    <h1>Projects</h1>
</div>

<div class="projects-grid">
  {% for post in site.posts %}
    {% if post.categories contains "project" %}
      <div class="project-item">
        <a href="{{ post.url }}">
          <h2>{{ post.title }}</h2>
          <p class="post-date">{{ post.date | date: "%B %d, %Y" }}</p>
          <p>{{ post.excerpt }}</p>
          <div class="tags">
            {% for tag in post.tags %}
              <span class="tag">{{ tag }}</span>
            {% endfor %}
          </div>
        </a>
      </div>
    {% endif %}
  {% endfor %}
</div>