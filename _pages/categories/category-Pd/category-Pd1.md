---
title: "Series"
layout: archive
permalink: categories/Series # 똑같이 맞추기
author_profile: true 
sidebar_main: true
---


{% assign posts = site.categories.Series %} 
{% for post in posts %} {% include archive-single2.html type=page.entries_layout %} {% endfor %}


