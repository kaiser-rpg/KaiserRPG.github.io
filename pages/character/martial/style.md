---
title: Style Module
permalink: char_martial_module_style.html
---

These modules increase your combat effectiveness by reducing the penalties for performing certain maneuvers or learning completely new ones. Experience Points spent on style modules are counted toward the limit for the Martial Group.

{% for module in site.data.modules.style %}
<p>
{% include case/module.html module=module%}
</p>
{% endfor %}