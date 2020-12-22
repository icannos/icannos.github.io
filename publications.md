---
layout: default
title: Publications
---

{% for publications in site.publications %}

<a href="{{ publications.url | prepend: site.baseurl }}">
  <h2>{{ publications.title }}</h2>
</a>

<p class="post-excerpt">{{ publications.description | truncate: 160 }}</p>

{% endfor %}  
