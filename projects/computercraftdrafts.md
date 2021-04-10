---
title: ComputerCraft Drafts
layout: project
repo: https://github.com/NonlinearFruit/ComputerCraftDrafts
badges:
  - https://img.shields.io/github/languages/top/NonlinearFruit/ComputerCraftDrafts
  - https://img.shields.io/github/stars/NonlinearFruit/ComputerCraftDrafts
  - https://img.shields.io/github/issues/NonlinearFruit/ComputerCraftDrafts
  - https://img.shields.io/github/last-commit/NonlinearFruit/ComputerCraftDrafts
---

{% for repository in site.github.public_repositories %}
  {% if repository.html_url == page.repo %}
    - MATCH Found
    {% assign page.description = repository.description %}
  {% endif %}
{% endfor %}
- {{ page.description }}

Software written and TDD'd in Minecraft (via the mod ComputerCraft)

{% for p in site.pages %}
  {% if p.repo == page.repo %}
    - {{ page.description }}
  {% endif %}
{% endfor %}
