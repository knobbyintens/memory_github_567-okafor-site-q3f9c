---
layout: default
title: Engagements
permalink: /engagements/
---

# Engagements

{% assign items = site.engagements | sort: "year" | reverse %}
{% for engagement in items %}
## [{{ engagement.title }}]({{ engagement.url | relative_url }})

{{ engagement.client }} — {{ engagement.year }}
{% endfor %}
