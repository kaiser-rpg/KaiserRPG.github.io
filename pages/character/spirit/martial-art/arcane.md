---
title: Arcane Martial Arts
permalink: char_spirit_martial_art_arcane.html
toc: false
---

{% assign list = site.data.spirit.martialArt | where: "level", "arcane" | sort:"name" %}
{% for art in list %}
{% include case/martial-art.html art=art %}
{% endfor %}