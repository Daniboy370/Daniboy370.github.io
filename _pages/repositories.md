---
layout: repositories
title: repositories
permalink: /repositories/
description: Open-source GNC software, autonomous flight control, and navigation toolkits.
nav: true
nav_order: 3
---

{% if site.data.repositories.github_repos %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-between">
    {% for repo in site.data.repositories.github_repos %}
      {% include repository/repo.liquid repository=repo %}
    {% endfor %}
  </div>
{% endif %}
