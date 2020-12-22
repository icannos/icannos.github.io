---
layout: default
title: Teaching
---

{% for talks in site.teaching %}

<a href="{{ teaching.url | prepend: site.baseurl }}">
  <h2>{{ teaching.title }}</h2>
</a>

<p class="post-excerpt">{{ teaching.description | truncate: 160 }}</p>

{% endfor %}  
