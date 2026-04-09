---
layout: page-custom
title: Projects
permalink: /projects/
---

I use this space to share how I think about data. Some things are still a work in progress.

## Selected Work

<div class="project-grid">
  {% for project in site.data.projects %}
    <div class="project-card">
      <h3>{{ project.title }}</h3>
      <p>{{ project.description }}</p>

      {% if project.tech %}
        <p class="project-tech">{{ project.tech }}</p>
      {% endif %}

      <div class="project-links">
        {% if project.link and project.link != "#" %}
          <a href="{{ project.link | relative_url }}" class="project-link">View Project</a>
        {% endif %}

        {% if project.repo %}
          <a href="{{ project.repo }}" class="project-link" target="_blank" rel="noopener noreferrer">Repository</a>
        {% endif %}
      </div>
    </div>
  {% endfor %}
</div>

<!-- Feel free to include later

- Multi-Metric Evaluation Framework  
- Time Series Monitoring  
- Experimentation Workflow  
- Machine Learning Project

  -->

