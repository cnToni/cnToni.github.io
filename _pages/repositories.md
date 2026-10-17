---
layout: page
permalink: /repositories/
title: repositories
description: open-source code repositories behind my projects.
nav: true
nav_order: 4
---

## Featured repository

[gzfls-cantonese.net](https://github.com/gzfls-cantonese/gzfls-cantonese.net) is an open-source TypeScript project for *品三國 · 識粵語*, a website for exploring Cantonese storytelling recordings and practicing Cantonese pronunciation. It contains 157 episodes and 39,173 aligned transcript segments from Zhang Yuekai's well-known recordings of *Romance of the Three Kingdoms*. The source code is licensed under the MIT License, while the Cantonese corpus is derived from [CanCLID/zoengjyutgaai](https://huggingface.co/datasets/CanCLID/zoengjyutgaai), licensed under CC0 1.0.


{% include figure.liquid
  path="assets/img/gzfls-cantonese-net.png"
  alt="Screenshot of the gzfls-cantonese.net homepage showing the Cantonese pingshu episode archive"
  class="img-fluid rounded z-depth-1"
  width="80%"
  avoid_scaling=true
  zoomable=true
  caption="Homepage of <a href='https://gzfls-cantonese.net'>gzfls-cantonese.net</a> — 品三國 · 識粵語, An archive of 157 Cantonese storytelling episodes with 39,173 aligned transcript segments."
%}

{% if site.data.repositories.github_users %}

## GitHub users

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for user in site.data.repositories.github_users %}
    {% include repository/repo_user.liquid username=user %}
  {% endfor %}
</div>

---

{% if site.repo_trophies.enabled %}
{% for user in site.data.repositories.github_users %}
{% if site.data.repositories.github_users.size > 1 %}

  <h4>{{ user }}</h4>
  {% endif %}
  <div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% include repository/repo_trophies.liquid username=user %}
  </div>

---

{% endfor %}
{% endif %}
{% endif %}

{% if site.data.repositories.github_repos %}

## GitHub Repositories

<div class="repositories d-flex flex-wrap flex-md-row flex-column justify-content-between align-items-center">
  {% for repo in site.data.repositories.github_repos %}
    {% include repository/repo.liquid repository=repo %}
  {% endfor %}
</div>
{% endif %}
