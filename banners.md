---
layout: default
title: Banner Showcase
permalink: /banners.html
---

{% for banner in site.banners %}
  <div class="banner-card">
    <a href="{{ banner.url }}">
      <img src="{{ banner.image }}" alt="{{ banner.title }}">
    </a>
    <h3>{{ banner.title }}</h3>
  </div>
{% endfor %}