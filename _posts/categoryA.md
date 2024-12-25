---
title: "카테고리A"
layout: archive
permalink: /categoryA
---

{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}