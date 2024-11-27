---
layout: default
title: Projects Archive
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

---