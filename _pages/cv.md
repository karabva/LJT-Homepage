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
* Ph.D. in Computer Science, Hong Kong University of Science and Technology, 2024-Present
* B.Eng., Shanghai Jiao Tong University, 2020-2024

Work experience
======
* Research Intern, MINIMAX (February 2025 - Present)
* Research Intern, Tencent WXG (June 2024 - September 2024)
  * Advisor: Zifei Shan
* Research Intern, Shanghai AI Lab (June 2023 - December 2023)
  * Advisor: Prof. Yu Cheng

Research Interests
======
* Natural Language Processing
* Machine Learning
* LLM Reasoning and Reinforcement Learning
* Hallucination in Vision-Language Models (VLM)
* LLM truthfulness and Interpretability

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
  
Awards
======
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Service and leadership
======
* Reviewer for various NLP and ML conferences
