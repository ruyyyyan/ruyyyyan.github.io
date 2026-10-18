---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* **Ph.D. in Theoretical Physics** (硕博连读), Soochow University (苏州大学), 2026 – Present
* **M.S. in Theoretical Physics**, Soochow University (苏州大学), 2024 – 2026
* **B.S. in Physics**, Soochow University (苏州大学), 2020 – 2024

Research Interests
======
* Ferroelectric physics and 2D sliding ferroelectricity
* Nonlinear dynamics and chaotic behaviors in low-dimensional systems
* First-principles calculations (DFT) and effective Hamiltonian methods
* Strongly correlated electron systems and superconductivity

Skills & Methodologies
======
* **Theoretical & Computational Physics**: Density Functional Theory (DFT), First-principles calculations, Effective Hamiltonian construction, Nonlinear dynamics analysis
* **Physics Topics**: Ferroelectrics, 2D Materials, Strongly Correlated Systems, Superconducting physics
* **Scientific Computing & Tools**: Python, Linux / Bash, Git, High-Performance Computing (HPC) clusters

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks & Presentations
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
