---
title: Research Projects
layout: page
---

{% for project in site.research %}
  <h2>{{ project.title }}</h2>
  <h3>{{ project.time }}</h3>
  <h4><a href="{{ project.link }}">GitHub link</a></h4>
  <p>{{ project.content | markdownify }}</p>
{% endfor %}