---
layout: archive
title: "Sitemap"
permalink: /sitemap/
author_profile: true
---

{% include base_path %}

## Pages

- [About]({{ '/' | relative_url }})
- [Research]({{ '/research/' | relative_url }})
- [Teaching]({{ '/teaching/' | relative_url }})

## Research Papers

<ul>
{% for paper in site.publications reversed %}
  <li><a href="{{ paper.url | relative_url }}">{{ paper.title | escape }}</a></li>
{% endfor %}
</ul>
