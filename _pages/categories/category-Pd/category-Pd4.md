---
title: "Groupy 및 일괄처리 메소드"
layout: archive
permalink: categories/Groupy # 똑같이 맞추기
author_profile: true
sidebar_main: true
---



{% assign posts = site.categories.Groupy %}
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}