---
tags: [page]
---

<h1>Articles by tag :{{ page.tags }}</h1>

 {% for post in site.tags.menu %}
            <a href="{{ post.url }}/">{{ post.title }}</a>
 {% endfor %}
