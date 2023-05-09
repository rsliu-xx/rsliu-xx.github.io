---
permalink: /
title: "Liu Ruishuang"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

### Short Bio

I’m a Ph.D. candidate at [Harada Lab.](https://www.roboticmanipulation.org/), in [Osaka Unversity](https://www.osaka-u.ac.jp/ja), supervised by Professor [Harada Kensuke](http://www.hlab.sys.es.osaka-u.ac.jp/people/harada/) and Professor [Wan Weiwei](https://wanweiwei07.github.io/). My research interest is robotic manipulation. I received my M.E. from Nanyang Technologic University and B.E. from Tianjin University, China.

### Research Interest
My major interest is robotic manipulation, which include grasping planning, motion planning, and other low level and high level task planning algorithms. I am also studying visual perception, image processing and force control to enhance the robotic manipulation system. 

### Research
<div class="container">
    <div class="video">
        <h3>Robotic 3D Drawing</h3>
        <a href="https://www.youtube.com/watch?v=DwUWdWQCZyw&t=61s" target="_blank">
            <img src="https://img.youtube.com/vi/DwUWdWQCZyw/maxresdefault.jpg" alt="Amazing Video" width="320" height="180" border="10" />
        </a>
    </div>
    <div class="text">
        <p>This video shows a flexible and robust robotic system for autonomous drawing on 3D surfaces. The system takes 2D drawing strokes and a 3D target surface (mesh or point clouds) as input. It maps the 2D strokes onto the 3D surface and generates a robot motion to draw the mapped strokes using visual recognition, grasp pose reasoning, and motion planning. The system is flexible compared to conventional robotic drawing systems as we do not fix drawing tools to the end of a robot arm. Instead, a robot selects drawing tools using a vision system and holds drawing tools for painting using its hand. Meanwhile, with the flexibility, the system has high robustness thanks to the following fine crafts: First, a high-quality mapping method is developed to minimize deformation in the strokes. Second, visual detection is used to re-estimate the drawing tool's pose before executing each drawing motion. Third, force control is employed to avoid noisy visual detection and calibration, and ensure a firm touch between the pen tip and a target surface. Fourth, error detection and recovery are implemented to deal with unexpected problems. The planning and executions are performed in a closed-loop manner until the strokes are successfully drawn. The clips in the video demonstrate all the mentioned flexibility and robustness.  </p>
    </div>
</div>

<div class="container">
    <div class="video">
        <h3>Metal Wire Manipulation Planning for 3D Curving</h3>
        <a href="https://www.youtube.com/watch?v=sp4KDs7oiEw" target="_blank">
            <img src="https://img.youtube.com/vi/sp4KDs7oiEw/maxresdefault.jpg" alt="Amazing Video" width="320" height="180" border="10" />
        </a>
        <a href="https://www.youtube.com/watch?v=u3PL-W4Xhjo" target="_blank">
            <img src="https://img.youtube.com/vi/u3PL-W4Xhjo/maxresdefault.jpg" alt="Amazing Video" width="320" height="180" border="10" />
        </a>
    </div>
    <div class="text">
        <p>This video presents a combined task and motion planner for a robot arm to carry out 3D metal wire curving tasks by collaborating with a bending machine. We assume a collaborative robot that is safe to work in a human environment but has a weak payload to bend objects with large stiffness, and developed a combined planner for the robot to use a bending machine. Our method converts a 3D curve to a bending set and generates the feasible bending sequence, machine usage, robotic grasp poses, and pick-and-place arm motion considering the combined task and motion level constraints. Compared with previous deformable linear object shaping work that relied on forces provided by robotic arms, the proposed method is suitable for the material with high stiffness. We evaluate the system using different tasks. The results show that the proposed system is flexible and robust to generate robotic motion to corporate with the designed bending machine. </p>
    </div>
</div>
