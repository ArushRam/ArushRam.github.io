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
---------
* B.S. in Computer Science, University of California, 2024
    * _Minor:_ Bioinformatics
    * _GPA:_ 3.947
    * _Honors:_ Dean's Honor List (Winter '21 - Fall '23), Shivakumar Endowed Scholarship in Computer Science, Upsilon Pi Epsilon, Tau Beta Pi

Work experience
---------------
* Machine Learning Research Intern, Rahmani Lab UCLA _(May 2023 - Present)_
  * First-authoring new contrastive optimization algorithm for improved generalization on out-of-distribution data.
  * Implemented several variants of algorithm in TensorFlow available for use with any gradient-based model.
  * Conducted several experiments with various gradient filtering criteria, aggregation methods and developed adaptive learning rate methods based on cosine similarities and subset sizes for improved generalization performance.
  * Created and visualized several diagnostic metrics including Jaccard indices for monitoring subset stability and graph-visualizations of final gradient coefficients across domains to identify intrinsic biases in dataset across multiple points in loss landscape.
  * Achieved 5% improvement on median AUC performance on CONVERGE voice-recording datasets and matched benchmarks on Camelyon-17-WILDS.
  * Supervisor: [Prof. Elior Rahmani](https://eliorrahmani.com/home.html)

* Machine Learning Research Intern, Bouchard Lab UCLA _(May 2022 - Present)_
    * Implemented Gauss-Newton and Levenberg-Marquardt second-order optimization algorithms in TensorFlow to use in explainable AI models for landslide prediction.
    * Trained a 2-stage neural network aggregating multiple ResNets on the MSTAR radar image dataset with all inbuilt PyTorch optimizers and achieved accuracies exceeding 98%, matching literature.
    * Automated model tracking by writing scripts to parse hundreds of cluster job log files for model information, hyperparameters and performance measures and store results in csv files.
    * Working on fast matrix inversion for second order optimization algorithms.
    * Supervisor: Prof. Louis Bouchard

* Flight Software Engineer, Unmanned Aerial Systems at UCLA _(April 2022 - April 2023)_
    * Led development on "Ground Station" dashboard displaying live telemetry and map position from a remote drone and ground vehicle for AUVSI SUAS inter-collegiate unmanned drone competition.
    * Researched and implemented motion planning algorithm for fixed-wing aircraft for AUVSI-SUAS Competition 2023.
    * Wrote automated camera scripts to capture and process images for classification as part of competition objectives.

* Frontend Developer at ACM Teach LA _(October 2021 - August 2022)_
    * Produced several tutorial pages and ‘Terminal’ React component simulating Linux CLI for learning lab used to train ~40 ACM Cyber members and event participants in Linux fundamentals annually.
    * Designed and made Cartesian-coordinate exercises replicating Turtle movement for Teach LA’s Introduction to Python curriculum taught at a series of local schools.

* Student Researcher at Pioneer Academics _(April 2019 - August 2019)_
    * Studied materials theory pertaining to strength, fracture mechanics, thermodynamics and quantum mechanics.
    * Learnt molecular dynamics simulator packages LAMMPS and OVITO and ran atomistic simulations for various Aluminum alloys with Copper and Magnesium.
    * Analyzed simulation data using Python and materials theory to evaluate tensile strength-fracture toughness tradeoff of Aluminum.
    * Conveyed findings in a [research paper](https://arushram.github.io/files/PioneerAcademicsPaper.pdf) graded 97/100 by Prof. Frank Peiris of Kenyon College and shortlisted for publication in the Pioneer Research Journal.


Activities
----------
* Writing Assistant for Bioinformatics Textbook _(April 2023 - June 2023)_
  * Wrote chapter on dimension reduction via PCA and t-SNE for use in single-cell methods for CS CM121 course taught by [Prof. Harold Pimentel](https://pimentellab.com/authors/harold_pimentel/).
* Upsilon Pi Epsilon _(Oct 2021 - Present)_
  * Tutor undergraduate students in Computer Science, Math and Physics for two hours every week.
  
Skills
------
* __Programming Languages__: Python, C++, C, JavaScript, TypeScript, Lisp, Shell, Ruby, SQL
* __Machine Learning__: PyTorch, TensorFlow, JAX, CUDA, Scikit-Learn, Matplotlib, Seaborn
* __Data__: PostgreSQL, Apache Spark, MongoDB, MapReduce
* __Web Development__: React, Node, Express, Mongoose, Jekyll, WebGL
* __Software__: Git, Docker, Linux, LaTeX

<!-- Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!--   
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
