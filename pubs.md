---
layout: page
title: Publications
permalink: /pubs/
---

{% for pub in site.pubs %}
* [{{ pub.title }}]({{pub.url}})
{% endfor %}
