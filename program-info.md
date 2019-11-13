---
title: Incentive Program Descriptions
permalink: /incentive/programs
---

{% for program in site.data.program-info %}
{% for member in program %}

{% comment %}
When using yaml object (not array), an extra iteration happens for the key itself
and produces an empty tag
{% endcomment %}
{% if member.name != null %}
### {{ member.name }}
{:.mb-3}
{{ member.description }}

{% endif %}

{% endfor %}

{% endfor %}