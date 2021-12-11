---
title: Bücher-Rezensionen
layout: books
permalink: /books/
---

hallo papi 2

{% for book in site.data.books %}
# {{ book.titel}} - {{ book.untertitel}}
## von {{ book.autor}}
<a href="{{ book.rezension }}">Buchbeschreibung</a>
{% endfor %}


buch eins

dfba 
ldkgjaölbj

buch zwei
bla 
blak

