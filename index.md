---
layout: default
title: Angela Ortiz
---
# Angela Ortiz

I am a researcher working on data systems and interactive intelligence.

## Publications

{% for pub in site.publications %}
- [{{ pub.title }}]({{ pub.url }}) — {{ pub.venue }}, {{ pub.year }}
{% endfor %}
