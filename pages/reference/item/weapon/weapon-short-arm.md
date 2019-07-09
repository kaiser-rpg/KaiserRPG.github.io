---
title: Short Arms
permalink: ref_weapon_short_arm.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Short Arm" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
