---
title: Thaumic Module
permalink: char_magic_module_thaumic.html
---

Experience Points spent on Thaumic Modules are counted toward the limit for the Magic Group.

{% for module in site.data.modules.thaumic %}
<p>
{% include case/module.html module=module%}
</p>
{% endfor %}