---
title: Maces
permalink: ref_weapon_mace.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Mace" and weapon.group contains "Classic" %}
{% include case/weapon.html weapon=weapon %}
{% endif %}
{% endfor %}