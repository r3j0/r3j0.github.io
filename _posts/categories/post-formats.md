---
title: "Post Formats"
layout: archive
permalink: categories/post-formats
---

{% assign posts = site.categories.blog %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}