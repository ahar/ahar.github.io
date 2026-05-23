---
layout: page
title: Sparse 3D LiDAR & Dynamic-Scene Planning
description: PhD research on programmable 3D sensing, dynamic object estimation, and adaptive motion planning.
img: assets/img/refined_surfel.png
importance: 1
category: research
---

## Problem

Autonomous robots operating in dynamic indoor environments must perceive, track, and plan around moving obstacles using cost-effective sensors — often sparse 3D data from modified 2D LiDAR rather than expensive multi-beam units.

## Approach

As part of my PhD at the **IIT Bombay–Monash University Research Academy**, I developed an end-to-end pipeline:

- **Programmable 3D LiDAR** — nodding 2D LiDAR with reconfigurable mirrors for dense 3D coverage and faster scan updates than conventional 2D LiDAR
- **Two-stage dynamic object estimation** — GMM-based real-time coarse tracking and shape estimation, followed by Kalman filtering for precise state estimation with arbitrary shape and motion primitives from sparse 3D data
- **Adaptive BIT\*** — real-time motion planning among multiple dynamic obstacles in partially unknown environments
- **Physics-based simulation** — evaluation framework for planning under varying obstacle density

## Results

- Publications in **IEEE RA-L / IROS 2018** and **Elsevier Mechatronics (2023)**
- Presented at **IROS 2018**, Madrid (SDC travel grant)
- Related work on anytime motion planning ([arXiv:1912.13461](https://arxiv.org/abs/1912.13461))

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/refined_surfel.png" title="Dynamic object shape estimation" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/inlier_outlier.png" title="Sparse 3D point cloud processing" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
