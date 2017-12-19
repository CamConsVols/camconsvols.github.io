---
title: Bar
layout: cheese
---
# Bar

{% avatar chris-ccv %}

{{ site.time }}

{% for s in data.sites %}
  {{ s.name }}
{% endfor %}
