---
layout: post
title:  "Dynamics Based Hand Tracking"
date:   2019-01-01 22:21:59 +00:00
highlight: true
image: /images/012_CR_IROS_FogROS_FT.png
# animate: /videos/011_CR_ICRA_Chess16.mp4
categories: CR
author: "Nan Tian"
venue: "Graphics Interfaces"
authors: "Stan Melax, <strong>Leonid Keselman</strong>, Sterling Orsten"
# subtitle: "Dynamics based 3D skeletal hand tracking"
website: https://sites.google.com/view/fogros2-ft
arxiv: https://autolab.berkeley.edu/assets/publications/media/2024_IROS_FogROS2_FT_final.pdf
code: https://github.com/KeplerC/FogROS2-FT
---

IROS 2024 Best Student Paper Finalist, 
<br>
(Congrads. Eric!)

Using a physics engine (e.g. a dynamics solver) to track 3D articulated objects in real-time. 

<blockquote>
  <p>
    This research explores a new approach to tracking hands, or any articulated model, by using an augmented rigid body simulation. This allows us to phrase 3D object tracking as a linear complementarity problem with a well-defined solution. Based on a depth sensor&#8217;s samples, the system generates constraints that limit motion orthogonal to the rigid body model&#8217;s surface. These constraints, along with prior motion, collision/contact constraints, and joint mechanics, are resolved with a projected Gauss-Seidel solver. Due to camera noise properties and attachment errors, the numerous surface constraints are impulse capped to avoid overpowering mechanical constraints. To improve tracking accuracy, multiple simulations are spawned at each frame and fed a variety of heuristics, constraints and poses. A 3D error metric selects the best-fit simulation, helping the system handle challenging hand motions.
  </p>
</blockquote>
