---
layout: page
permalink: /repositories/
title: repositories
hide_header: true
nav: true
nav_order: 4
---

{%- assign repos = site.data.repositories -%}

<p>
  Changes are submitted and reviewed on GerritHub:
  <a href="{{ repos.gerrit_host }}/admin/repos/q/filter:{{ repos.gerrit_owner }}">browse all {{ repos.gerrit_owner }} projects</a>.
</p>

{% for group in repos.groups %}
<h2 class="category">{{ group.name }}</h2>
<div class="card-grid mb-4">
  {%- for repo in group.repos %}
  {%- assign full_name = repos.gerrit_owner | append: '/' | append: repo.name %}
  <div>
    <div class="card hoverable h-100">
      <div class="card-body">
        <h3 class="card-title h5">
          <a href="{{ repos.gerrit_host }}/admin/repos/{{ full_name }}">{{ repo.name }}</a>
        </h3>
        <p class="card-text">{{ repo.description }}</p>
      </div>
    </div>
  </div>
  {%- endfor %}
</div>
{% endfor %}
