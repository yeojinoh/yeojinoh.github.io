---
layout: archive
permalink: categories/English
title: "English"
sidebar_main: true
---
{% assign posts = site.categories.English %}
{% for post in posts %} {% include archive-single.html type=page.entries_layout %} {% endfor %}