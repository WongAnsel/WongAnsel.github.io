---
title: "Projects"
permalink: /projects/
layout: archive
---

# My Data Science Projects

Here are some of my recent data science and machine learning projects.

{% for post in site.posts %}
  {% if post.categories contains 'projects' %}
    <article class="archive-item">
      <h2><a href="{{ post.url }}">{{ post.title }}</a></h2>
      <p>{{ post.excerpt }}</p>
    </article>
  {% endif %}
{% endfor %}
