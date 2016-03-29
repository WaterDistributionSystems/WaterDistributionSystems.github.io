---
layout: page
title: People
permalink: /people/
---

{% for person in site.people %}
* [{{ person.title }}]({{person.url}})
{% endfor %}
