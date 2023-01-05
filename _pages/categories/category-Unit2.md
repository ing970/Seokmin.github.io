---
title: "플레이데이터 2강"
layout: archive
permalink: categories/Unit2 # 똑같이 맞추기
author_profile: true
sidebar_main: true
---



{% assign posts = site.categories.Unit2 %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}