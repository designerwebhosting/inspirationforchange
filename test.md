---
tags: [page]
categories: [test,another]
---

##Articles by tag :{{ page.tags }}

 {% for p in site.tags.page %}
  {{ p.title }}  {{ p.tags }}
  {% endfor %}
  
## categories

{% for p in site.category.test %}
  {{ p.title }}  {{ p.tags }}
  {% endfor %}
  
##pages

{% for p in site.pages %}
  {{ p.title }}  {{ p.tags }}
  {% endfor %}
