---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D. in Computer Science, Ohio State University, 2025-2029 (expected)
* M.S. in Computer Science, Ohio State University, 2024-2025
* B.S. in Computational Neuroscience, Ohio State University, 2020-2023

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Industry Experience
======
* Wexner Medical Center - Data Scientist - Supervisor: Dr. Jay Fournier (Aug. 2023 - Present)
  * Led code implementation for two preprints and a conference presentation
  * Released behavioral scoring software for four neuroimaging tasks utilized across universities
  * Designed a novel algorithm to quantify and display missing data from 3D and 4D brain images
  * Automated a Slurm pipeline to process six terabytes of neuroimaging data
  * Developed a sequential denoising algorithm to achieve state of the art noise removal from rs-fMRI data

* JP Morgan Chase and Co - Data Science Intern - Supervisor: Ritwik Chatterjee (June 2023 - Aug. 2023)
  * Collaborated with four cross-functional teams to create a data flow standard to facilitate product discovery
  * Provided direction for two agile scrum teams by prioritizing backlog and planning sprints
  * Analyzed current technical capabilities to deliver a roadmap for explainable fraud decisioning

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Python, PyTorch, HuggingFace, vLLM, Slurm (High Performance Computing), MATLAB, R
  
Service and leadership
======
* coming soon
