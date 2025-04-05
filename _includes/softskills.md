| Skill | Level |
| ---- | ---- |
{% assign skills = sites.data.skills.soft | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}
