---
tags: [page]
categories: [test,another]
layout: default
---

{% assign tags_list = site.tags %}

{% for tag in tags_list %}
      
        {{ tag }}
{% endfor %}
