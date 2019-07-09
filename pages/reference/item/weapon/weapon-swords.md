---
title: Swords
permalink: ref_weapon_sword.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Sword" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
