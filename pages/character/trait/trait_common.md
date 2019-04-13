---
title: Common Traits
keywords: sample
summary: "This is just a sample topic..."
permalink: trait_common.html
trait_group: common
---

### Positive Traits

{% for trait in site.data.trait.common.positive %}
    {% include trait.html trait=trait %}
{% endfor %}


### Negative Traits

{% for trait in site.data.trait.common.negative %}
    {% include trait.html trait=trait %}
{% endfor %}