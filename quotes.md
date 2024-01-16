---
layout: default
title: /quotes
permalink: /quotes
---

A collection of quotes I find interesting or inspiring.

{% for item in site.quotes reversed %} 
  <blockquote>"{{ item.content }}" ({{item.quote_author}})</blockquote>
{% endfor %}