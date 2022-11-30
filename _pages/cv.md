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
* B.Tech. in Electrical Engineering (Power and Automation), Indian Institute of Technology Delhi, 2015-2019
* M.S. in Computer Science, University of California San Diego, 2021-2023

Work experience
======
* AI/ML Intern, Apple Seattle, June 2022 - Sept. 2022
  * Developed a new tool as part of the CoreMLTools team to convert a deep learning model defined in JAX to CoreML.
  * Implemented transformations for 40 tensor operations defined in JAX to efficiently map to the existing CoreML ops.
  * Optimized and tested the existing framework to successfully convert heavy JAX models like GPT2, CLIP and ViT.

* Research Engineer, Illinois at Singapore (UIUC), June 2019 - Nov 2020
  * Developed a training framework in pytorch and caffe for extreme quantization of low parameter deep learning models like
    SkyNet, which on 2,4-bit quantization outperformed the winner of DAC 2020 on both performance and model size.
  * Designed a parameter search algorithm to find optimal FPGA tiling parameters for deployment of deep learning models
    using Monte Carlo method. Developed a visualization system to track the tile parameters and load division on FPGAs.
  * Evaluated competing compression methods for large scale transformer based language models like BERT [TACL 21].

* Software Engineering Intern, Arcesium India, May 2018 - July 2018
  * Designed a model in Java and ActiveMQ to horizontally scale the financial data processing engine on multiple nodes.
  * Developed a sql based relationship handling system to handle dependency issues arising as a result of parallel processing

Papers and Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* 
* Programming Languages: Python, Java, C++, Latex
* ML frameworks: Pytorch, Tensorflow, JAX
* Softwares: MATLAB, SIMULINK

Service and leadership
======
* BloodConnect 2016-2018: Helped manage and organize community blood donation drives in New Delhi
