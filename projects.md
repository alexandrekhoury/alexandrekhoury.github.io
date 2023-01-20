---
layout: page
title: Projects
permalink: /projects/
---
<div class="projects">
  {% for project in site.static_files %}
    {% if project.path contains 'projects' %}
    <div class="project">
      <h2><a href="{{ project.path }}">{{ project.title }}</a></h2>
    </div>
    {% endif %}
  {% endfor %}
</div>