---
layout: post
title:  "Dynamics Based Hand Tracking"
date:   2024-09-01 22:21:59 +00:00
image: /images/005_CR_PLR24.jpg
animate: /videos/005_CR_PLR24.mp4
categories: CR
author: "Nan Tian"
venue: "Graphics Interfaces"
authors: "Stan Melax, <strong>Leonid Keselman</strong>, Sterling Orsten"
subtitle: "Dynamics based 3D skeletal hand tracking"
arxiv: https://arxiv.org/abs/1705.07640
code: https://github.com/IntelRealSense/hand_tracking_samples
---

Using a physics engine (e.g. a dynamics solver) to track 3D articulated objects in real-time. 

<blockquote>
  <p>
    This research explores a new approach to tracking hands, or any articulated model, by using an augmented rigid body simulation. This allows us to phrase 3D object tracking as a linear complementarity problem with a well-defined solution. Based on a depth sensor&#8217;s samples, the system generates constraints that limit motion orthogonal to the rigid body model&#8217;s surface. These constraints, along with prior motion, collision/contact constraints, and joint mechanics, are resolved with a projected Gauss-Seidel solver. Due to camera noise properties and attachment errors, the numerous surface constraints are impulse capped to avoid overpowering mechanical constraints. To improve tracking accuracy, multiple simulations are spawned at each frame and fed a variety of heuristics, constraints and poses. A 3D error metric selects the best-fit simulation, helping the system handle challenging hand motions.
  </p>
</blockquote>
