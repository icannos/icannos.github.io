---
layout: default
title: Talks
---

{% for talks in site.talks %}

<a href="{{ talks.url | prepend: site.baseurl }}">
  <h2>{{ talks.title }}</h2>
</a>

<p class="post-excerpt">{{ talks.description | truncate: 160 }}</p>

{% endfor %}  
