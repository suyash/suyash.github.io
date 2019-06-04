## [Certifications](#certifications)

{% for c in site.data.certifications %}

__[{{c.name}}]({{c.link}})__<br>
{{c.provider}}

{% endfor %}
