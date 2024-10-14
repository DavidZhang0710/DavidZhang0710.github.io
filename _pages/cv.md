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
  * Designed a non-intrusive parameter serialization component based on C++ macros and Templates, and added pre-validation to ensure parameter integrity. Implemented auto-expanding serializing with only a 7KB increase in package size and decreased API crash rates by 0.2% through robust parameter validation
  * Built a tool to automatically generate API documentation from annotated header files. Utilized Doxygen and RapidXML parser to parse definitions and comments from header files. Converted parsed information into a custom JSON format to support C++ overloading and multi-platform compatibility
  * Developed a Message Bus module only based on C++ STL and multi-threading libraries, implemented synchronous and asynchronous sending methods, and involved queues to optimize and simplify the asynchronous sending method, reducing response time of multi-stream APIs by 6.9%
  
Skills
======
* Programming Language
  * Java, C, C++, Python, SQL, JavaScript, Vue.js, CSS, HTML
* Technology
  * Spring & Spring Boot, Flask, Redis, Zookeeper, Kafka, RabbitMQ, Javassist, CMake, scikit-learn
* Tools
  * Git, Docker, Maven, Linux, AWS, Postman

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>