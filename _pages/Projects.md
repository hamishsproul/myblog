---
title: Projects
layout: default
permalink: /projects/
---
<h1>Projects</h1>
<ul>
  {% for project in site.categories %}
    <li>
      <h2>{{ project[0] }}</h2>
      <ul>
        {% for post in project[1] %}
          <li><a href="{{ post.url }}">{{ post.title }}</a></li>
        {% endfor %}
      </ul>
    </li>
  {% endfor %}
</ul>
