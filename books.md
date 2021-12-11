---
title: Bücher-Rezensionen
layout: books
permalink: /books/
---
{% for book in site.data.books %}
# {{ book.titel}} - {{ book.untertitel}}
## von {{ book.autor}}
<a href="{{ book.rezension }}">Buchbeschreibung</a>
{% endfor %}