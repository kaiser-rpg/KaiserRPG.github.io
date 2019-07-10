---
title: Mind Module
permalink: char_manifest_module_mind.html
---

Experience Points spent on Mind Modules are counted toward the limit for the Manifest Group.

{% for module in site.data.modules.mind %}
<p>
{% include case/module.html module=module%}
</p>
{% endfor %}