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

  ---

## Publications

### Thesis
- **The Role of Test Locations in Early-Stage Plant Breeding: Identifying Discriminating Locations and Extrapolating Performance to Locations that are Not Observed**  
  <a href="https://www.proquest.com/openview/17e34e37039da0b91eb619c5a49d15fe/1?pq-origsite=gscholar&cbl=18750&diss=y" target="_blank">
    View Thesis
  </a>

### Research Papers

- **A Regression Approach to Identify Discriminating Locations**  
  *Crop Science, Volume 63, Issue 2*  
  Hanisha Vemireddy, Sigurdur Olafsson  
  <a href="https://acsess.onlinelibrary.wiley.com/doi/full/10.1002/csc2.20873" target="_blank">
    View Publication
  </a>

- **A Method for Approximate Rank Confidence Intervals in Plant Breeding Experiments**  
  *Heliyon, Volume 11, Issue 5, March 2025*  
  Reyhaneh Bijari, Hanisha Vemireddy, Sigurdur Olafsson  
  <a href="https://www.cell.com/heliyon/fulltext/S2405-8440(25)01354-4" target="_blank">
    

