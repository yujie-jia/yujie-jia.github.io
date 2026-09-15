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
I am currently a first-year master's student in the Data Science and Information Technology program at Tsinghua Shenzhen International Graduate School. I am a member of MMLabSZ, advised by Prof. Zhi Wang.

Previously, I received my bachelor's degree in Software Engineering from South China University of Technology.

My research interests mainly focus on Vision-Language Navigation (VLN), with a particular interest in dense reward modeling and long-horizon navigation in real-world environments.

I am enthusiastic about exploring emerging technologies and innovative applications. Feel free to reach out if you are interested in discussing ideas or potential collaborations.

Research
------
<div>
  <table>
  {% for post in site.research reversed %}
    {% unless post.hidden %}
    <tr>{% include research.html %}</tr>
    {% endunless %}
  {% endfor %}
  </table>
</div>

Projects
------
<div>
  <table>
  {% for post in site.projects reversed %}
    {% unless post.hidden %}
    <tr>{% include project.html %}</tr>
    {% endunless %}
  {% endfor %}
  </table>
</div>

# 🏆 Award
* <b>2025:</b> National Scholarship of SCUT
* <b>2024:</b> National Scholarship of SCUT
* <b>2023:</b> Macau Alumni Association Scholarship of SCUT

# 🎯 Misc
------
* 🏀 Addicted to playing BASKETBALL！(Superfan of Kyrie & Harden)<br>
* 🎹 Playing the electronic keyboard, 📚 reading (e.g., GEB), 🎬 watching anime (e.g., Arcane, Attack on Titan, Cyberpunk: Edgerunners), and 🎲 playing board games.<br>



