---
layout: default
title: Projects
permalink: /projects/
---

# Projects Archive

Welcome to my project archive! Here, you can explore all my blog posts and case studies, organized by month and year. Dive in to see how I’ve tackled complex challenges and delivered impactful solutions.

---

## Explore Projects

{% assign postsByYearMonth = site.posts | group_by_exp: "post", "post.date | date: '%B %Y'" %}
{% for yearMonth in postsByYearMonth %}
  ### {{ yearMonth.name }}
  <ul class="project-list">
    {% for post in yearMonth.items %}
      <li>
        <a href="{{ post.url }}" class="project-link">{{ post.title }}</a>
      </li>
    {% endfor %}
  </ul>
{% endfor %}

<style>
/* Archive Page Styles */
body {
  font-family: 'Arial', sans-serif;
  line-height: 1.6;
}

h1 {
  text-align: center;
  margin-bottom: 1.5rem;
}

h2, h3 {
  color: #007acc;
  margin-top: 2rem;
}

.project-list {
  margin: 1rem 0 2rem 1.5rem;
  list-style-type: disc;
}

.project-link {
  font-size: 1.1rem;
  color: #007acc;
  text-decoration: none;
}

.project-link:hover {
  text-decoration: underline;
  color: #005f99;
}
</style>