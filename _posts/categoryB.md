---
title: "카테고리B"
layout: archive
permalink: /categoryB
---

{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}