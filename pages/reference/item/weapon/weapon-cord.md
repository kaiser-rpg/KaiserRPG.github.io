---
title: Cords
permalink: ref_weapon_cord.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Cord" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}