---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

[Download CV (PDF)](/files/Bidhan%20Biswas%20CV.pdf)

Education
======
* M.Sc. in Computer Science and Engineering, Dhaka International University, Dhaka, Bangladesh, Expected June 2027 (In Progress)
* B.Sc. in Computer Science and Engineering, Sylhet Engineering College, Sylhet, Bangladesh, 2018 — CGPA: 3.77/4.00, awarded with Distinction
  * Affiliated with Shahjalal University of Science and Technology (SUST)
  * Undergraduate thesis: “Brain Tumor Detection with Tumor Region Analysis Using Adaptive Thresholding and Morphological Operation.”
  * Supervisor: Prof. M. J. Islam, SUST

Research Experience
======
* **Data-Efficient and Cross-Dataset Learning for Biomedical Imaging**
  * Developed a few-shot cross-dataset adaptation framework for tuberculosis detection using DenseNet-121 under limited target-domain labels.
  * Evaluated zero-shot transfer, frozen-head adaptation, full fine-tuning, and scratch-training regimes across varying numbers of target-domain examples.
  * Conducted research on medical image analysis spanning brain tumor detection, tuberculosis detection, diabetic retinopathy grading, and breast histopathology.

* **Reliable Machine Learning for Clinical and Mental-Health Applications**
  * Cost-sensitive mental-health text classification with emphasis on reducing harmful misclassification under cross-domain transfer.
  * Selective safety-aware routing layer that defers uncertain suicide-risk predictions for human review using asymmetric misclassification costs.

Professional Experience
======
* **Senior Officer (IT), Online Banking Division**, Janata Bank PLC, Motijheel, Dhaka, Bangladesh (2021–Present)
  * Develop and maintain eJanata, the bank’s internet banking platform serving over 200,000 users nationwide.
  * Built core modules of JB360, an internal portal used across business divisions for reporting, reconciliation, and dispute resolution.
  * Technology stack: Python, Django, REST APIs, Oracle.

* **Assistant Programmer**, ICT Centre, Bangladesh University of Professionals (BUP), Dhaka, Bangladesh (Feb. 2020–Mar. 2021)
  * Designed and developed CHSR, a web platform for the Centre for Higher Study and Research.
  * Technology stack: PHP, MySQL.

* **Junior Software Developer**, BitMorpher, Dhaka, Bangladesh (2018–2020)
  * Developed native iOS applications in Objective-C and Swift for graphic design and image enhancement.
  * Implemented image-processing and rendering features for the applications.

Skills
======
* **Machine Learning:** PyTorch, Pandas, NumPy, Matplotlib
* **Programming:** Python, C/C++, Java, SQL
* **Software:** Swift, Objective-C, iOS SDK, PHP, Oracle, MySQL

Awards & Activities
======
* Fundamental IT Engineer (FE), Level 2 — Bangladesh IT Engineers Examination Center (BD-ITEC), 2019
* National Collegiate Programming Contest (NCPC), University of Asia Pacific, 2016
* Inter-University Programming Contest, BUET, 2015
* Inter-University Programming Contest, State University of Bangladesh, 2015
* IUT 6th National ICT Fest, Islamic University of Technology, 2014

Publications
======
{% assign ordered_publications = site.publications | sort: 'pub_order' %}
  <ul>{% for post in ordered_publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
