---
title: Shields
permalink: ref_weapon_shield.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Shield" and weapon.group contains "Classic" %}
{% include case/weapon.html weapon=weapon %}
{% endif %}
{% endfor %}