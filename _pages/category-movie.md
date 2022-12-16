---
layout: archive
title: "Movie"
permalink: /movie
author_profile: true
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories.movie %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}