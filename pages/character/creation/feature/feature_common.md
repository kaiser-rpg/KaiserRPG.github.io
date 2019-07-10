---
title: Common Features
permalink: char_feature_common.html
---

### Positive Features
{% assign positiveFeature = site.data.features.common.positive | sort: "name" %}

{% for feature in positiveFeature %}
{% include character/feature.html feature=feature %}
{% endfor %}


### Negative Features

{% assign negativeFeature = site.data.features.common.negative | sort: "name" %}

{% for feature in negativeFeature %}
{% include character/feature.html feature=feature %}
{% endfor %}