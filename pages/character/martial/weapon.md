---
title: Weapon Modules
permalink: char_martial_module_weapons.html
---

Weapon modules allow you to gain proficiency with additional weapons.

{% for module in site.data.modules.weapon %}
<p>
{% include case/module.html module=module%}
</p>
{% endfor %}