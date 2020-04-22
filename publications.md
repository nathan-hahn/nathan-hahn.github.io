---
layout: page
title: Publications
permalink: /publications/
---

{% for pub in site.publications %}
  {% if pub.authors contains "Nathan Hahn" %}
  {{ publications.content | }}
  {% endif %}
{% endfor %}
