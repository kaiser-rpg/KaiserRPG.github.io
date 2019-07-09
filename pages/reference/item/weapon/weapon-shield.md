---
title: Shields
permalink: ref_weapon_shield.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Shield" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
