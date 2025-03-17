---
layout: default
title: "Projects"
permalink: /projects/
css_class: "projects-page"
---

# All Projects

---
<!-- Filter Buttons -->
<div class="project-filters">
  <button data-filter="all" onclick="filterAllProjects('all')">All</button>
  <button data-filter="professional" onclick="filterAllProjects('professional')">Professional</button>
  <button data-filter="personal" onclick="filterAllProjects('personal')">Personal</button>
</div>

<!-- All Projects (sorted by category and date) -->
<div class="all-gallery">
  {%- comment -%}
  First, create two groups: professional and personal. Each is sorted by date (newest first).
  {%- endcomment -%}
  {% assign professional_projects = site.projects | where:"category", "professional" | sort:"date" | reverse %}
  {% assign personal_projects = site.projects | where:"category", "personal" | sort:"date" | reverse %}
  {% assign sorted_projects = professional_projects | concat: personal_projects %}
  
  {% for project in sorted_projects %}
    {% assign s = project.status | default: "" %}
    {% if s contains "under_construction" %}
      <!-- Non-clickable item -->
      <div class="project-item" data-category="{{ project.category }}">
        <div class="under-construction-banner">
          🚧 Under Construction 🚧
        </div>
        {% if s contains "new" %}
          <div class="corner-ribbon">New!</div>
        {% endif %}
        {% if project.header_image %}
          <img src="{{ project.header_image | relative_url }}" alt="{{ project.title }}">
        {% endif %}
        <h2>{{ project.title }}</h2>
        <p>{{ project.description }}</p>
      </div>
    {% else %}
      <!-- Clickable item (data-category added) -->
      <a class="project-item" data-category="{{ project.category }}" href="{{ project.url }}">
        {% if s contains "new" %}
          <div class="corner-ribbon">New!</div>
        {% endif %}
        {% if project.header_image %}
          <img src="{{ project.header_image | relative_url }}" alt="{{ project.title }}">
        {% endif %}
        <h2>{{ project.title }}</h2>
        <p>{{ project.description }}</p>
      </a>
    {% endif %}
  {% endfor %}
</div>

<script>
function filterAllProjects(category) {
  // Only select items within the all-gallery
  const items = document.querySelectorAll('.all-gallery .project-item');
  items.forEach(item => {
    if (category === 'all') {
      item.style.display = 'block';
    } else {
      const cat = item.getAttribute('data-category');
      // Compare in lower case after trimming whitespace
      item.style.display = (cat.trim().toLowerCase() === category.toLowerCase()) ? 'block' : 'none';
    }
  });

  // Highlight the correct button
  const buttons = document.querySelectorAll('.project-filters button');
  buttons.forEach(btn => {
    btn.classList.remove('active');
    if (btn.dataset.filter.toLowerCase() === category.toLowerCase()) {
      btn.classList.add('active');
    }
  });
}

document.addEventListener('DOMContentLoaded', () => {
  filterAllProjects('all');
});
</script>
