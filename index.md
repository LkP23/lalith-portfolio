---
title: "Lalith Krishna Prakash Parsa"
layout: splash
permalink: /

# --- Header Banner ---
header:
  overlay_color: "#000"
  overlay_filter: "0.45"
  overlay_image: "/assets/profile.jpg"
  actions:
    - label: "Explore My Research"
      url: "/research/"
    - label: "View Publications"
      url: "/publications/"

excerpt: >
  Ph.D. Applicant in Computer Science | Artificial Intelligence • Data Analytics • Machine Learning | Academic Portfolio

# --- Feature Cards Section ---
feature_row:
  - image_path: /assets/projects/p2.jpg
    alt: "AI & Computer Vision Research"
    title: "AI & Computer Vision Research"
    excerpt: "Deep learning, image recognition, and intelligent automation for real-world problem solving."
    url: "/research/"
    btn_label: "View Projects"
    btn_class: "btn--primary"

  - image_path: /assets/projects/p4.jpg
    alt: "Data Engineering and Analytics"
    title: "Data Engineering & Analytics"
    excerpt: "ETL pipelines, data modeling, and visualization using Python, SQL, and BI tools."
    url: "/research/"
    btn_label: "Learn More"
    btn_class: "btn--info"

  - image_path: /assets/projects/p6.jpg
    alt: "Teaching and Mentorship"
    title: "Teaching & Mentorship"
    excerpt: "Encouraging students to explore AI, Data Science, and Software Engineering through guided learning."
    url: "/teaching/"
    btn_label: "See Courses"
    btn_class: "btn--success"
---

<section class="hero">
  <h1>Welcome</h1>
  <p>
    I’m <strong>Lalith Krishna Prakash Parsa</strong>, a <strong>Ph.D. Applicant in Computer Science</strong> 
    passionate about <strong>Artificial Intelligence</strong>, <strong>Data Analytics</strong>, and <strong>Computer Vision</strong>.
  </p>

  <p>
    This academic portfolio showcases my journey across:
  </p>
  <ul>
    <li>🔬 Research and technical projects</li>
    <li>📘 Academic publications</li>
    <li>🧑‍🏫 Teaching and mentoring experience</li>
    <li>📄 Professional and educational background</li>
  </ul>

  <div class="quick-links">
    <a href="{{ '/research/' | relative_url }}">🔬 Research</a>
    <a href="{{ '/publications/' | relative_url }}">📘 Publications</a>
    <a href="{{ '/teaching/' | relative_url }}">🧑‍🏫 Teaching</a>
    <a href="{{ '/cv/' | relative_url }}">📄 CV</a>
    <a href="{{ '/contact/' | relative_url }}">✉️ Contact</a>
  </div>
</section>

{% include feature_row id="feature_row" %}
