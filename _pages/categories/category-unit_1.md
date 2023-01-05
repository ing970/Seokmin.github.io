---
title: "Play_dat_1강"
layout: archive
permalink: categories/Unit1 # 똑같이 맞추기
author_profile: true
sidebar_main: true
---



{% assign posts = site.categories.Unit1 %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}