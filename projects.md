```md id="h3zv8n"
---
layout: page-custom
title: Projects
permalink: /projects/
---

I use this space to showcase the different ways I work with data, from solving real-world business problems to building technical skills through hands-on coding and research.

---

## Industry Data Science Work

These projects reflect my experience applying statistics, experimentation, and analytical modeling to improve decision-making in real-world settings.

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

---

## SQL & Python Learning Projects

I am actively building a GitHub portfolio of learning projects to deepen my hands-on coding skills in SQL, Python, and machine learning. These projects reflect my continued investment in strengthening practical implementation skills alongside my analytical experience.

<div class="project-grid">

  <div class="project-card">
    <h3>SQL Data Analysis Projects</h3>
    <p>
      Exploratory SQL projects focused on joins, window functions, aggregations, and business-style analytical problem solving.
    </p>
    <p class="project-tech">SQL</p>
    <div class="project-links">
      <a href="YOUR_GITHUB_SQL_LINK" class="project-link" target="_blank" rel="noopener noreferrer">Repository</a>
    </div>
  </div>

  <div class="project-card">
    <h3>Python Predictive Modeling Practice</h3>
    <p>
      Hands-on machine learning projects exploring regression, classification, feature engineering, and model evaluation using public datasets.
    </p>
    <p class="project-tech">Python, Pandas, Scikit-learn</p>
    <div class="project-links">
      <a href="YOUR_GITHUB_PYTHON_LINK" class="project-link" target="_blank" rel="noopener noreferrer">Repository</a>
    </div>
  </div>

</div>

---

## Research & Publications

My research work focuses on statistical modeling, regression methods, and experimental design, with applications in agricultural decision-making and breeding optimization.

### Doctoral Thesis

### Improving Early-Stage Plant Breeding Decisions Through Predictive Modeling
Developed statistical frameworks to identify high-value testing environments and predict performance in unobserved locations, improving efficiency in experimental planning.

<a href="https://www.proquest.com/openview/17e34e37039da0b91eb619c5a49d15fe/1?pq-origsite=gscholar&cbl=18750&diss=y" target="_blank">
View Thesis
</a>

---

### Publications

#### A Regression Approach to Identify Discriminating Locations
Designed regression-based methodology to identify the most informative agricultural test locations, improving resource allocation efficiency in breeding experiments.  
*Crop Science, Volume 63, Issue 2*  
Hanisha Vemireddy, Sigurdur Olafsson  

<a href="https://acsess.onlinelibrary.wiley.com/doi/full/10.1002/csc2.20873" target="_blank">
View Publication
</a>

---

#### A Method for Approximate Rank Confidence Intervals in Plant Breeding Experiments
Developed statistical confidence interval methods to improve ranking reliability in plant breeding comparisons under uncertainty.  
*Heliyon, Volume 11, Issue 5, March 2025*  
Reyhaneh Bijari, Hanisha Vemireddy, Sigurdur Olafsson  

<a href="https://www.cell.com/heliyon/fulltext/S2405-8440(25)01354-4" target="_blank">
View Publication
</a>
```
