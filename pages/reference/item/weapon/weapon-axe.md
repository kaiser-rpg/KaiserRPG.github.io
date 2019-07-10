---
title: Axes
permalink: ref_weapon_axe.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Axe" and weapon.group contains "Classic" %}
{% include case/weapon.html weapon=weapon %}
{% endif %}
{% endfor %}