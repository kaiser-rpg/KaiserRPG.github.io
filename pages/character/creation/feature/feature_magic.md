---
title: Magic Features
permalink: char_feature_magic.html
---

### Positive Features

{% for feature in site.data.features.magic.positive %}
    {% include character/feature.html feature=feature %}
{% endfor %}


### Negative Features

{% for feature in site.data.features.magic.negative %}
    {% include character/feature.html feature=feature %}
{% endfor %}