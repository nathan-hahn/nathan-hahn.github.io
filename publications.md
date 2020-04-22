---
layout: page
title: Publications
permalink: /publications/
---

{% for pub in site.publications %}
  {% if publications.authors contains "Nathan Hahn" %}
  {{ publications.content | markdownify }}
  {% endif %}
{% endfor %}
