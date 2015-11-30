---
tags: [page]
---

<h1>Articles by tag :{{ page.tags }}</h1>
<div>
    {% if site.tags[page.tags] %}
        {% for post in site.tags[page.tags] %}
            <a href="{{ post.url }}/">{{ post.title }}</a>
        {% endfor %}
    {% else %}
        <p>There are no posts for this tag.</p>
    {% endif %}
</div>


Page
 {% for post in site.tags.page %}
            <a href="{{ post.url }}/">{{ post.title }}</a>
 {% endfor %}
