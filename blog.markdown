---
layout: page
title: Blog
permalink: /blog/
---

## 📚 Todas las Publicaciones

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url }})

**{{ post.date | date: "%d de %B de %Y" }}**

{{ post.excerpt | strip_html }}

[Leer más →]({{ post.url }})

---

{% endfor %}
