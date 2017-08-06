## [Experience](#experience)

{% for e in site.data.experience %}

{% if e.link %}
__[{{e.position}}]({{e.link}})__
{% else %}
__{{e.position}}__
{% endif %} <br> {{e.name}} — {{e.location}}<br>
_{{e.start}} — {{e.end}}_

{% endfor %}
