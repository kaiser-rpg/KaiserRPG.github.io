---
title: Fired
permalink: ref_weapon_fired.html
toc: false
---

{% assign weaponList = site.data.weapons.classic %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Firing" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}
