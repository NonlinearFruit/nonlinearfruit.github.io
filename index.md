# Projects

{% for page in site.pages %}
  {% if page.path contains 'project' %}
    {% include project-template.md project=page %}
  {% endif %}
{% endfor %}

Learn more about NonlinearFruit [here](about.md)
