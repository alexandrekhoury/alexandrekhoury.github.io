---
layout: page
title: Projects
permalink: /projects/
---
{% for project in site.projects %}
<div style="clear: both;">
  <h2> <a href="{{ project.url }}">{{ project.title }}</a></h2>
   <div style="float: left; margin-right 1em;">
    <img src="{{ project.image }}" alt="{{ project.title }}" width="200" height="150">
  </div>
  <p>{{ project.description }}</p>
</div>
{% endfor %}