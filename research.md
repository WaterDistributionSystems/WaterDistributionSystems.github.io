---
layout: page
title: Research
permalink: /research/
---

{% for project in site.research %}
* [{{ project.title }}]({{project.url}})
{% endfor %}
