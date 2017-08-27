## [Projects](#projects)

{% for e in site.data.projects %}

__[{{e.name}}]({% if e.github %} https://github.com/{{site.github_username}}/{{e.github}} {% else %} {{e.website}} {% endif %})__<br>
{{e.description}}

{% endfor %}
