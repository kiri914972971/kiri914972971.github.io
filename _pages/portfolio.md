---
layout: archive
title: "Projects"
permalink: /portfolio/
collection: portfolio
entries_layout: list
author_profile: true
author: academicpages
---

Here are some selected projects showcasing my work in data analysis, product thinking, and business insights.

{% assign projects = site.portfolio | sort: "date" | reverse %}
{% for post in projects %}
  {% include archive-single.html type="list" %}
{% endfor %}
