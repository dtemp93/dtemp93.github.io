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
* Ph.D in Machine Learning/Data Science, Technical University of Denmark, Cognitive Systems, 2018
* M.Sc. in Medicine and Technology, Technical University of Denmark, 2014
* B.Sc. in Medicine and Technology, Technical University of Denmark, 2011

Experience
======
* __Co-founder__, Siren IVS, www.siren.care, Copenhagen.
  * Developing a temperature sensings sock for prevention of diabetic foot ulcers. Worked for 6 months on the project but left to pursue a PhD.
* __Research Assistant__, DTU Compute, Kgs. Lyngby.
  * Working on the project Neuro 24/7, long term ear-EEG monitoring. Smartphone sensor capture and processing, speaker recognition, EEG experiments
* __Co-founder__, Cortrium, www.cortrium.com, Copenhagen.
  * Working on ICA de-noising, feature extraction and classification of two-lead w  
* __Software Developer__ in LabVIEW, Medimatic A/S, Hellerup.
  * Developed a program for data acquisition, organisation and processing to work with a distal blood pressure measurement device in hospitals.
  * Demonstration, sales and technical support in most of the major hospitals in Denmark.

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>

Tools
======
* Data
  * Numpy, Pandas, BColz, Dask, Bokeh
* Statistics
  * Stan, Edward, PyMC3
* Machine Learning
  * TensorFlow, PyTorch, Scipy, Scikit-learn

<!-- Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->