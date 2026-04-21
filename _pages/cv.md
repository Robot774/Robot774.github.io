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
* B.Eng. in Automation, Tsinghua University, 2022 – 2026 (expected)
* Ph.D. in Computer Science, MMLab@HKU, The University of Hong Kong, 2026 – (incoming), advised by Prof. Ping Luo, Prof. Hongyang Li, and Prof. Yi Ma

Research Interests
======
* Robotics
* Vision-Language-Action (VLA) Models
* World Models

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
