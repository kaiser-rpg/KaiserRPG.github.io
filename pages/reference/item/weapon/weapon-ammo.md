---
title: Ammo
permalink: ref_weapon_ammo.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Ammo" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
