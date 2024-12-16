---
title: Test
layout: default
permalink: /test/
---

<h1>Site Categories</h1>
<ul>
  {% for category in site.categories %}
    <li>{{ category[0] }}</li>
  {% endfor %}
</ul>
