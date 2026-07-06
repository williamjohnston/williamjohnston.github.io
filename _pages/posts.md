---
layout: archive
title: "All Posts"
permalink: /posts/
---

<hr>
<div class="container">
{% for post in site.posts %}
  {% include archive-single.html type="grid" %}
{% endfor %}
</div>
