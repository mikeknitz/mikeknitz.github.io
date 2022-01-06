---
layout: defaults/page
permalink: index.html
narrow: true
title: Home page
---

Home!

### Recent Posts

{% for post in site.posts limit:3 %}
{% include components/post-card.html %}
{% endfor %}