| Skill | Level |
| ---- | ---- |
{% assign skills = sites.data.skills.technical | sort: "title" -%}
{% for skill in skills -%}
| {{skill.title}} | {{skill.level}} |
{% endfor %}
