---
title: "Iterable과 Decorator"
layout: archive
permalink: categories/Unit10 # 똑같이 맞추기
author_profile: true
sidebar_main: true
---




{% assign posts = site.categories.Unit10 %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}