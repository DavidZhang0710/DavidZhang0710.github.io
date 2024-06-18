---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
PDF version here: [Huangyu's Curriculum Vitae](../files/Curriculum_Vitae.pdf).

Education
======
* M.S. in Computer Science, University of Southern California, 2024-2026 (expected)
* B.E. in Computer Science, Xi'an Jiaotong University, 2020-2024

Work experience
======
* Bytedance, C++ Software Development Internship, 2023.06-2023.10
  * Programmed in C++ to develop a module called MessageBus, which facilitated the handling of API call messages and asynchronous message dispatch, successfully reducing the API crash rate from 0.5% to 0.2%.
  * Programmed in Python to develop a module to automatically generate header files in other programming languages based on the C++ header files.
  * Programmed in C++ to develop a tool using Doxygen, which automatically generates API documentation from header files. The generated API documentation includes API definitions, descriptions, parameter types and ranges.
  * Designed and developed new Java and Objective-C APIs for multi-streaming.
  
Skills
======
* Programming Language
  * Java, C, C++, Python, JavaScript, SQL, CSS, HTML
* Software
  * Linux, Git, Docker, Redis, Kafka, Maven, OpenCV, MyBatis
* Frameworks/Tools
  * Spring Boot, Flask, Cmake, PyTorch, Scikit-Learn, Tensorflow, AWS Lambda Linux, Node.js, Vue.js

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>