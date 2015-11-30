---
tags: [page]
categories:
- test,
- another
layout: default
permalink: /test/
---
##Pages

{% for page in site.pages %}
{{ page }}
{% endfor %}
