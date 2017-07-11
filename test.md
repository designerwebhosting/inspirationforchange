---
title: "Ann Noble"
description: "You will free yourself from emotionally painful memories, switch off reoccurring unwanted thoughts and release yourselve from fear."
layout: index
categories:
tags:
---
<!---->{% for row in site.data.layouts.index %}
<div class="row">{% assign s = site.posts | size %}{% assign x = row.row | size %}{% assign columns = 12 | divided_by: x %}{% for c in row.row %}
<div class="col-md-{{ columns }}">{% assign col = s | minus: 1 | minus: c.story %}{% assign post = site.posts[col] %}
{% if c.title == true %}<h2>{{ post.title }}</h2>{% endif %}
{{ post.excerpt }}
</div>{% endfor %}
</div>{% endfor %}
