---
title: Poles
permalink: ref_weapon_pole.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Pole" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
