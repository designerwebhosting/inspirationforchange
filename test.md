---
tags: [page]
categories: [test,another]
---

##Articles by tag :{{ page.tags }}

 {% for p in site.tags.page %}
  {{ p }}{% endfor %}
  
## categories

{% for p in site.category.test %}
  {{ p }}{% endfor %}
  
##pages

{% for p in site.pages %}
  {{ p.title }}{{ p.title }}{% endfor %}
