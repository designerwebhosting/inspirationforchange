---
tags: [page]
categories: [test,another]
---

## Articles by tag :{{ page.tags }}

 {% for p in site.tags %}
  {{ p }}
 {% endfor %}
 ## categories
{% for p in site.category %}
  {{ p }}
 {% endfor %}
##pages
{% for p in site.pages %}
  {{ p }}
 {% endfor %}
