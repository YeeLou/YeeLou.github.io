---
permalink: /
title: "Yi Lu (芦毅)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Ph.D. student of [Computational Imaging Technology & Engineering Lab](https://cite.nju.edu.cn) at [Nanjing University](https://www.nju.edu.cn/en/). My research interests include human motion capture, motion understanding, human-robot interaction, humanoid robot motion control, and teleoperation.  

<section id="publications">
  <h2>Publications</h2>
  {% include base_path %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>  


<section id="projects">
  <h2>Projects</h2>
  {% include base_path %}
  {% for post in site.projects reversed %}
    {% include archive-single.html %}
  {% endfor %}
</section>
More details can be available at [MoCapHumanoid](https://shenqiu.njucite.cn/MoCapHumanoid/) and [Github](https://github.com/NJU-CITE-MoCapHumanoid). We look forward to having you join us and grow together. Experience with Python, PyTorch, Linux, and ROS is a plus.

<!-- [Robot Teleoperation](https://github.com/YeeLou/Robot-Teleoperation) -->
