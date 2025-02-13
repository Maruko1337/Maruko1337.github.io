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
* B.S. in University of Waterloo, Ontario, Canada, 2020-2025

Work experience
======
* January to August 2024: Data Scientist
  * University of Waterloo, Mechanical and Mechatronics Engineering Department
  * I developed a novel GNN-based method for river ice classification to support automated monitoring in Montreal. I
presented my research at Geoinformatics 2024, gave a 20-minute talk, and volunteered at the conference. 
  * Supervisor: Professor Andrea Scott

* April to September 2023: Research Assistant
  * University of Waterloo, Applied Math Department
  * I integrated first-order PDEs, like Advection and Burgers equations, into GNNs to tackle over-smoothing and enhance
performance in deep architectures. Collaborated with faculty and peers, contributing to discussions and technical reports.
  * Supervisor: Professor Hans De Sterck

* April to September 2022: Image Algorithm Engineer
  * Aqrose Technology
  * At Aqrose Technology, a company specialising in advanced image processing and AI solutions for industrial applications, I
developed a new algorithm for detecting data matrix codes in images, aiming for higher accuracy and reduced processing
time. This role enhanced my leadership and teamwork skills while allowing me to explore machine learning in computer
vision independently.

* September to December 2021: Research Assistant
  * Chinese Academy of Science, Institute of Semiconductors
  * Conducted research in underwater image processing at CAS, reviewing literature and developing a novel dehazing method.
Gained expertise in OpenCV and C++ and deepened knowledge of image processing techniques.
  
Skills
======
* Programming & Software Development
  * Python (NumPy, SciPy, PyTorch, TensorFlow)
  * C/C++ (OpenCV, Eigen)
  * MATLAB, Julia, Maple, SQL, Racket
  * Git, Linux System, Latex, Markdown, HTML
* Numerical Methods & Scientific Computing
  * Finite Element Methods (FEM), Finite Difference Methods (FDM)
  * Solvers for PDEs & BVPs (Crank-Nicolson, Advection-Diffusion models)
  * High-performance computing (HPC), mixed-precision computing
* Machine Learning & AI
  * Graph Neural Networks (GNNs), Geometric Deep Learning
  * Image Processing & Computer Vision (DCP-based dehazing, SAR image analysis)
  * Optimization techniques (SGD, Adam, Newton's method)
* Soft Skills & Communication
  * Research presentation & academic writing (Conference talks, papers)
  * Leadership & teamwork (Led a multicultural research team)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
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
  
Service and leadership
======
* Currently signed in to 43 different slack teams
