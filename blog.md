---
layout: default
title: Blog
permalink: /blog/
---

<h1 class="mm-hero-title">Blog</h1>
<div class="mm-rule"></div>



<div class="row g-3 mt-2">
{% for post in site.posts %}
  <div class="col-12">
    <div class="mm-card">
      <div class="d-flex justify-content-between flex-wrap gap-2">
        <div><a class="fw-semibold" href="{{ post.url | relative_url }}">{{ post.title }}</a></div>
        <div class="mm-small">{{ post.date | date: "%Y-%m-%d" }}</div>
      </div>
      {% if post.excerpt %}
        <div class="mm-small mt-2">{{ post.excerpt | strip_html | truncate: 180 }}</div>
      {% endif %}
    </div>
  </div>
{% endfor %}
</div>
