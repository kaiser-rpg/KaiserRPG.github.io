---
title: Baset
permalink: char_heritage_baset.html
toc: false
---

{% assign heritageOption = site.data.heritage.core | where:"name", page.title | first %}

{% include character/heritage.html heritage=heritageOption %}
