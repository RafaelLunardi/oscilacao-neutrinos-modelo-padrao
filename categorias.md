---
title: Categorias
permalink: /categorias/
---

## Temas do blog

{% assign all_categories = site.categories | sort %}
{% for category in all_categories %}
### {{ category[0] | capitalize }}

{% for post in category[1] %}
- [{{ post.title }}]({{ post.url | relative_url }}) — {{ post.date | date: "%d/%m/%Y" }}
{% endfor %}
{% endfor %}
