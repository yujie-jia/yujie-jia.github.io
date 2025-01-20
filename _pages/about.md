---
permalink: /
title: "👋 About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<br />
I am a third-year undergraduate student in the School of Software Engineering at South China University of Technology. I engage in developing an agent that can understand and interact with the multi-modal world. Toward this goal, my research mainly focus on:

* <b>Embodied AI</b>: Visual Navigation; Dexterous manipulation; 
* <b>Multi-Modal Large Models</b>: Multi-Agent Systems; Retrieval-Augmented Generation (RAG); Knowledge Refinement for Long-Text Data

Research
------
<div>
  <table>
  {% for post in site.research reversed %}
    <tr>{% include research.html %}</tr>
  {% endfor %}
  </table>
</div>

Projects
------
<div>
  <table>
  {% for post in site.projects reversed %}
    <tr>{% include project.html %}</tr>
  {% endfor %}
  </table>
</div>

# 🏆 Award
* <b>2024:</b> National Scholarship of SCUT
* <b>2024:</b> Hongping Evergreen Scholarship of SCUT
* <b>2023:</b> Macau Alumni Association Scholarship of SCUT
 