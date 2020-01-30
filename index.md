# Dev Edmonton Society RFCs

## Draft

These RFCs are new the society and undergoing development and review. They have not been formally endorsed but are shared in a spirit of collaboration and openess.

{% for rfc in site.rfcs %}
 * [RFC-{{ rfc.RFC }}: {{ rfc.title }}]({{ rfc.url }})
{% endfor %}