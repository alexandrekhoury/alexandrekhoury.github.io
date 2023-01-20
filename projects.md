---
layout: page
title: Projects
permalink: /projects/
---
<div class="projects">
  {% for project in site.collections %}
    {% if project.label == "projects" %}
    <div class="project">
      <h2><a href="{{ project.url }}">{{ project.title }}</a></h2>
      <p>{{ project.description }}</p>
    </div>
    {% endif %}
  {% endfor %}
</div>