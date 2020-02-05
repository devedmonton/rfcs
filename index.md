# Dev Edmonton Society RFCs

## Drafts

These RFCs are new to the society and undergoing development and review. They have not been formally endorsed but are shared in a spirit of collaboration and openess.

{% assign draft_rfcs = site.rfcs | where: "status", "draft" %}
{% for rfc in draft_rfcs %}
 * [RFC-{{ rfc.RFC }}: {{ rfc.title }}]({{ rfc.url | relative_url }})
{% endfor %}