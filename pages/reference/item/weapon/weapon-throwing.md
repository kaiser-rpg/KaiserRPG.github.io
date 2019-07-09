---
title: Thrown
permalink: ref_weapon_thrown.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Throwing" or weapon.special contains "Throwable" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}