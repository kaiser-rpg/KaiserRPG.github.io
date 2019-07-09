---
title: Improvised and Unarmed
permalink: ref_weapon_improvised.html
toc: false
---

{% assign weaponList = site.data.items.weapons %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Unarmed" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}

{% for weapon in weaponList %}
{% if weapon.hide != true and weapon.weaponClass contains "Improvised" %}
{% include weapon.html weapon=weapon %}
{% endif %}
{% endfor %}