{% assign project = include.project %}
{% assign repo = site.github.public_repositories | where: "html_url", project.repo | first %}
- [{{ project.title }}]({{ project.url }}) » {{ project.description | default: repo.description }}
