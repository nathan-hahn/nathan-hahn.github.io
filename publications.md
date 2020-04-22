---
layout: page
title: Publications
---

{% for publications in site.publications reverse%}
  {% if publications.authors contains "Nathan Hahn" %}
  {{ publications.content }}
  {% endif %}
{% endfor %}
