---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<p align="center">
  <img src="../images/rbt.png" alt="" width="50" height="50">
</p>

## Short Bio

I’m a Ph.D. candidate at [Harada Lab.](https://www.roboticmanipulation.org/), in [Osaka Unversity](https://www.osaka-u.ac.jp/ja), supervised by Professor [Harada Kensuke](http://www.hlab.sys.es.osaka-u.ac.jp/people/harada/) and Professor [Wan Weiwei](https://wanweiwei07.github.io/). My research interest is robotic manipulation. I received my M.E. from Nanyang Technologic University and B.E. from Tianjin University, China.

## Research Interest
My major interest is robotic manipulation, which include grasping planning, motion planning, and other low level and high level task planning algorithms. I am also studying visual perception, image processing and force control to enhance the robotic manipulation system. 

## Research
<div class="container">
    <div class="video">
        <h3>Next Best View Planning Considering Confidence Obtained from Shape Completion Learning</h3>
        <a href="https://www.youtube.com/watch?v=QK22YEZGX-M&t=7s" target="_blank">
            <img src="https://img.youtube.com/vi/QK22YEZGX-M/maxresdefault.jpg" alt="YouTubeVideo" width="350" height="199" border="20" />
        </a>
    </div>
    <div class="text">
        <p> This video shows a Next Best Views (NBV) planner for capturing a thin, curved metal plate using a depth camera and a robot manipulator equipped with an external stationary depth sensor. The proposed approach aims to efficiently collect the object's surface point cloud data and reconstruct its 3D model with a minimal number of views. The challenge in obtaining the model of such objects lies in their shiny and flat surface, which leads to noisy point cloud data and low guidance in the surface normal for completion. To overcome these challenges, we propose using a Point cloud Completion Network (PCN) to find heuristics for NBV or Next Best robot Configuration (NBC) optimization. Unlike previous methods, our approach predicts NBV by considering a holistic view of the object predicted by neural networks, which is not limited by the local information captured by the sensors and is, therefore, robust to deficiencies in known point cloud data and normal.</p>
    </div>
</div>

<div class="container">
    <div class="video">
        <h3>Metal Wire Manipulation Planning for 3D Curving</h3>
        <a href="https://www.youtube.com/watch?v=sp4KDs7oiEw" target="_blank">
            <img src="https://img.youtube.com/vi/sp4KDs7oiEw/maxresdefault.jpg" alt="YouTubeVideo" width="350" height="199" border="20" />
        </a>
        <a href="https://www.youtube.com/watch?v=u3PL-W4Xhjo" target="_blank">
            <img src="https://img.youtube.com/vi/u3PL-W4Xhjo/maxresdefault.jpg" alt="YouTubeVideo" width="350" height="199" border="20" />
        </a>
    </div>
    <div class="text">
        <p>This video shows a combined task and motion planner (TAMP) for a robot arm to work with a bending machine in 3D metal wire curving tasks commonly found in manufacturing and medical fields. Our method converts a 3D curve to a bending set and generates the feasible bending sequence, machine usage, robotic grasp poses, and pick-and-place arm motion considering the combined task and motion level constraints. Compared with previous deformable linear object shaping work that relied on forces provided by robotic arms, the proposed method is suitable for the material with high stiffness. </p>
    </div>
</div>

<div class="container">
    <div class="video">
        <h3>Robotic 3D Drawing</h3>
        <a href="https://www.youtube.com/watch?v=DwUWdWQCZyw&t=61s" target="_blank">
            <img src="https://img.youtube.com/vi/DwUWdWQCZyw/maxresdefault.jpg" alt="Amazing Video" width="350" height="199" border="20" />
        </a>
    </div>
    <div class="text">
        <p>This video shows a flexible and robust robotic system for autonomous drawing on 3D surfaces. The system maps the strokes onto the surface and generates robot motion using visual recognition, grasp pose reasoning, and motion planning. Unlike conventional systems, the robot can recognize and pick up pens to draw 3D strokes, making it more flexible. The system's robustness is ensured by minimizing deformation in the strokes, re-estimating the drawing tool's pose, employing force control, and implementing error detection and recovery. The planning and executions are performed in a closed-loop manner. </p>
    </div>
</div>

