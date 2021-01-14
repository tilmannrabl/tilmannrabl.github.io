---
layout: default
title: Tilmann Rabl
---
# Tilmann Rabl

Head of [Data Engineering Systems Group](http://www.hpi.de/rabl) at [HPI](http://www.hpi.de)

## Publications 

See [Google Scholar](https://scholar.google.de/citations?user=BQvUJuYAAAAJ) 

[//]: # (This may be the most platform independent comment
{% for publication in site.publications limit:3 %}
* {{ publication.author }}: <a href="{{ publication.url }}">*{{ publication.title }}*</a>, in {{ publication.booktitle }}, {{ publication.year }}
{% endfor %}
)
