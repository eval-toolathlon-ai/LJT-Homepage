---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<h2>Education</h2>

<ul>
  <li>
    <strong>Ph.D. in Computer Science</strong> (2024 – Present)<br>
    Hong Kong University of Science and Technology<br>
    Advisor: Professor Junxian He
  </li>
  <li>
    <strong>B.Eng.</strong> (2020 – 2024)<br>
    Shanghai Jiao Tong University
  </li>
</ul>

<h2>Research Experience</h2>

<ul>
  <li>
    <strong>Research Intern</strong>, MINIMAX (February 2025 – Present)
  </li>
  <li>
    <strong>Research Intern</strong>, Tencent WXG (June 2024 – September 2024)<br>
    Advisor: Zifei Shan
  </li>
  <li>
    <strong>Research Intern</strong>, Shanghai AI Lab (June 2023 – December 2023)<br>
    Advisor: Prof. Yu Cheng
  </li>
</ul>

<h2>Publications</h2>

{% assign publications = site.publications | sort: 'date' | reverse %}
{% for post in publications %}
  {% include archive-single-cv.html %}
{% endfor %}

<h2>Awards</h2>

<ul>
  <li>
    <strong>Zhiyuan Honor Scholarship</strong><br>
    Shanghai Jiao Tong University
  </li>
</ul>

<h2>Skills</h2>

<ul>
  <li><strong>Research Areas:</strong> Natural Language Processing, Machine Learning, Large Language Models, Vision-Language Models</li>
  <li><strong>Research Topics:</strong> LLM Reasoning, Reinforcement Learning, Hallucination Mitigation, Model Interpretability, Model Truthfulness</li>
</ul>
