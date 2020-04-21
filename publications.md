---
layout: page
title: Publications
permalink: /publications/
---

{% for pub in site.publications reversed %}
  {% if pub.authors contains "Nathan Hahn" %}
  {{ pub.content }}
  {% endif %}
{% endfor %}
