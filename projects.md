---
permalink: /projects/
title: "Projects"
excerpt: "Things I've built."
layout: single
author_profile: true
---

{% assign projects = site.projects | sort: "title" %}
{% for project in projects %}
  <h3><a href="{{ project.url | relative_url }}">{{ project.title }}</a></h3>
  <p>{{ project.excerpt | markdownify | strip_html | truncate: 200 }}</p>
{% endfor %}
