---
layout: page
title: Publications
---

{% for publications in site.publications %}
  {% if publications.authors contains "Nathan Hahn" %}
  {{ publications.content }}
  {% endif %}
{% endfor %}
