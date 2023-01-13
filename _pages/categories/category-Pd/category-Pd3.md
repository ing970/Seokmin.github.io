---
title: "정렬 및 집계"
layout: archive
permalink: categories/Sort # 똑같이 맞추기
author_profile: true
sidebar_main: true
---



{% assign posts = site.categories.Sort %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}