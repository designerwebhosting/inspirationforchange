---
title: Posts
description: posts for Christopher Byrne.
tags: 
---

<div>{% for post in site.posts %}
<div>
<a href="{{ post.url }}"><h2>{{ forloop.rindex0 }} {{ post.title }}</h2></a>
<p>{{ post.description }}</p>
</div>
<hr />{% endfor %}
</div>
