---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}

Preprints
===========
<span style="color:red">[Preprint]</span>: [Metal Wire Manipulation Planning for 3D Curving -- How a Low Payload Robot Can Use a Bending Machine to Bend Stiff Metal Wire](https://arxiv.org/pdf/2203.04024), Ruishuang Liu, Weiwei Wan, Emiko Tanaka Isomura, and Kensuke Harada, Arxiv: https://arxiv.org/pdf/2203.04024, 2022. [Video](https://youtu.be/sp4KDs7oiEw)

Journal
======
[Multi-Pen Robust Robotic 3D Drawing Using Closed-Loop Planning](https://arxiv.org/pdf/2009.14501.pdf), Ruishuang Liu, Weiwei Wan, Keisuke Koyama, and Kensuke Harada, arXiv: 2009.14501 [cs.RO], 2020. [Video](https://www.youtube.com/watch?v=KBSWHh4RtW0) [page](https://rsliu-xx.github.io/_pages/rbtdraw.html)(Reported by [IEEE Spectrum Video Friday](https://spectrum.ieee.org/automaton/robotics/robotics-hardware/video-friday-mesmer-humanoid-robot))

Domestic Conference
===========
Planning 3D Robotic Drawing, Ruishuang LIU, Weiwei WAN, Keisuke KOYAMA,Kensuke HARADA, 第38回日本ロボット学会学術講演会予稿集, 1I3-01，2020/10/9-11

Optimizaiton-based Planning and Control for 3D Robotic Drawing, Ruishuang LIU, Weiwei WAN, Keisuke KOYAMA,Kensuke HARADA, 第39回日本ロボット学会学術講演会予稿集, 1I3-01，2021/09/9-10

Award
===========
"Planning 3D Robotic Drawing", Finalist of the 2nd International Session Best Presentation Award, 日本ロボット学会, 2020/10/10.
