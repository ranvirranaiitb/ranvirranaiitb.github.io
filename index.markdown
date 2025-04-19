---
layout: single
permalink: /
author_profile: true
classes:
  - landing
  - wide
---

<div class="content-container">
  <h2>About Me</h2>
  <p>I am an academic researcher specializing in systems thinking, innovation management, and technology strategy. With a background in both theoretical frameworks and practical applications, my research explores the intersection of organizational systems and technological innovation. I hold a PhD in Systems Engineering from IIT Bombay and have published extensively in leading international journals.</p>
  
  <h2>Current Positions</h2>
  <ul>
    <li>Associate Professor, Department of Management Studies, XYZ University</li>
    <li>Research Fellow, Center for Innovation Studies</li>
    <li>Academic Advisor, Technology Strategy Institute</li>
  </ul>
</div>

## Selected Publications

<div class="grid__wrapper">
  {% assign sorted_publications = site.publications | sort: "date" | reverse %}
  {% for publication in sorted_publications limit:3 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div class="see-all-link">
  <a href="/publications/" class="btn btn--primary">View All Publications</a>
</div>

## Recent Talks

<div class="grid__wrapper">
  {% assign sorted_talks = site.talks | sort: "date" | reverse %}
  {% for talk in sorted_talks limit:3 %}
    {% include archive-single.html type="grid" %}
  {% endfor %}
</div>
<div class="see-all-link">
  <a href="/talks/" class="btn btn--primary">View All Talks</a>
</div>

## Research Focus
My research focuses on understanding complex systems and their applications in organizational innovation. Current projects include:

- Systems approaches to technology adoption in enterprises
- Innovation ecosystems and their development patterns
- Strategic frameworks for emerging technologies integration
