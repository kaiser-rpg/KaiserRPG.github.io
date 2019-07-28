---
title: Magic Features
permalink: char_feature_magic.html
---

### Positive Features

{% assign positiveFeature = site.data.features.magic.positive | sort: "name" %}

{% for feature in positiveFeature %}
{% include character/feature.html feature=feature %}
{% endfor %}


### Negative Features

{% assign negativeFeature = site.data.features.magic.negative | sort: "name" %}

{% for feature in negativeFeature %}
{% include character/feature.html feature=feature %}
{% endfor %}