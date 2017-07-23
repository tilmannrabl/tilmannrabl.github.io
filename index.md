---
layout: default
title: Tilmann Rabl
---
Tilmann Rabl
------------
Visiting Professor and Research Director at [DIMA Group](http://www.dima.tu-berlin.de), [TU Berlin](http://www.tu-berlin.de)

## Publications 

{% for publication in site.publications limit:3 %}
* {{ publication.author }}: *{{ publication.title }}*, in {{ publication.booktitle }}, {{ publication.year }}
{% endfor %}

