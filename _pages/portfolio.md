---
layout: archive
title: "Projects"
permalink: /portfolio/
author_profile: true
---

Here are some selected projects showcasing my work in data analysis, product thinking, and business insights.

{% assign projects = site.portfolio | sort: "date" | reverse %}

{% for p in projects %}
### [{{ p.title }}]({{ p.url | relative_url }})

{% if p.excerpt %}{{ p.excerpt }}{% endif %}

[View Project →]({{ p.url | relative_url }})

---
{% endfor %}
