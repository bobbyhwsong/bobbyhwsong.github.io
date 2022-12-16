---
layout: archive
title: "Code"
permalink: /code
author_profile: true
sidebar:
    nav: "sidebar-category"
---

{% assign posts = site.categories.code %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}