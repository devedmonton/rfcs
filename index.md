# Dev Edmonton Society RFCs

## Proposals

These RFCs have not been submitted to a Working Group for review and are being shared for collaboartion and feedback purposes only. They may not progress further, and could be withdrawn or rejected at any time. Expect major changes.

{% assign proposal_rfcs = site.rfcs | where: "status", "proposal" %}
{% for rfc in proposal_rfcs %}
 * [RFC-{{ rfc.RFC }}: {{ rfc.title }}]({{ rfc.url | relative_url }})
{% endfor %}

## Drafts

These RFCs are new to the society and undergoing development and review. They have not been formally adopted but being actively developed. As with proposals, they may not progress further and could be withdrawn or rejected at any time. Expect major changes.

{% assign draft_rfcs = site.rfcs | where: "status", "draft" %}
{% for rfc in draft_rfcs %}
 * [RFC-{{ rfc.RFC }}: {{ rfc.title }}]({{ rfc.url | relative_url }})
{% endfor %}