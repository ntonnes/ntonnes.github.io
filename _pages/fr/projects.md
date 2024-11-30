---
layout: page
title: Projets
permalink: /fr/projects/
lang: fr
---

<h1>{{ page.title }}</h1>

<div class="projects-grid">
  {% for post in site.posts %}
    {% if post.categories contains "project" and post.lang == page.lang %}
      <div class="project-item">
        <a href="{{ post.url }}">
          <h2>{{ post.title }}</h2>
          <dt class="post-date">{{ post.date | date: "%B %d, %Y" }}</dt>
          <p>{{ post.excerpt }}</p>
              <div class="tags">
                {% for tag in post.tags %}
                  {% assign tag_image = "/assets/tags/" | append: tag | append: ".png" %}
                  {% if tag_image | relative_url | file_exists %}
                    <img src="{{ tag_image | relative_url }}" alt="{{ tag }}" class="tag-image">
                  {% else %}
                    <span class="tag">{{ tag }}</span>
                  {% endif %}
                {% endfor %}
              </div>
        </a>
      </div>
    {% endif %}
  {% endfor %}
</div>