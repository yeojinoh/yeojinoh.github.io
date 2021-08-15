---
layout: archive
permalink: categories/Python
title: "Python"
sidebar_main: true
---

{% assign posts = site.categories.Python %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}