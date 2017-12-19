---
title: Bar
layout: cheese
---
# Bar

{% avatar chris-ccv %}

{{ site.time }}

# Sites

{% for s in site.data.sites %}
  {{ s.name }}
{% endfor %}

## end of sites
