---
layout: page
title: Publications
---

{% assign sorted = (site.publications | sort: 'date') | reverse %}
{% for pubs in sorted %}
  {% if pubs.authors contains "Nathan Hahn" %}
  {{ pubs.content }}
  {% endif %}
{% endfor %}
