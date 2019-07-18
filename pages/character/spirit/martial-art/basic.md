---
title: Basic Martial Arts
permalink: char_spirit_martial_art_basic.html
toc: false
---

{% assign list = site.data.spirit.martialArt | where: "level", "basic" | sort:"name" %}
{% for art in list %}
{% include case/martial-art.html art=art %}
{% endfor %}