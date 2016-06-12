---
layout: archive
title: "搞笑段子"
modified:
excerpt: "A collection of thoughts, inspiration, mistakes, and other minutia."
tags: []
image:
  feature:
  teaser:
---

<div class="tiles">
{% for post in site.categories.duanzi %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->