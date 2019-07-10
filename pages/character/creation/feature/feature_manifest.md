---
title: Manifest Features
permalink: char_feature_manifest.html
---

### Positive Features

{% for feature in site.data.features.manifest.positive %}
    {% include character/feature.html feature=feature %}
{% endfor %}


### Negative Features

{% for feature in site.data.features.manifest.negative %}
    {% include character/feature.html feature=feature %}
{% endfor %}