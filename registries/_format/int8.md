---
owner: MikeRalphson
issue: 845
description: signed 8-bit integer
base_type: number
layout: default
source: https://spec.openapis.org/oas/latest.html#data-types
source_label: OAS
---

# <a href="..">{{ page.collection }}</a>

## {{ page.slug }} - {{ page.description }}

Base type: `{{ page.base_type }}`.

The `{{page.slug}}` format represents a signed 8-bit integer, with the range -128 to 127.

{% if page.issue %}
### GitHub Issue

* [#{{ page.issue }}](https://github.com/OAI/OpenAPI-Specification/issues/{{ page.issue }})
{% endif %}

{% if page.remarks %}
### Remarks

{{ page.remarks }}
{% endif %}