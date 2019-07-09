---
title: Two-handed
permalink: ref_weapon_two_handed.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Two-handed" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
