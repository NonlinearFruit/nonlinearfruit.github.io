
# Github Repos

{% for repository in site.github.public_repositories %}
 - [{{ repository.name }}]({{ repository.html_url }}) » {{ repository.description }}
{% endfor %}

# Pages

```json
{{ site.pages }}
```

# Github Object

```json
{{ site.github }}
```

# Site

```json
{{ site }}
```
