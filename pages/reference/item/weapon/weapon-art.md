---
title: Impossible Weapons
permalink: ref_weapon_art.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.group contains "Art" %}
{% include case/weapon.html weapon=weapon %}
{% endif %}
{% endfor %}