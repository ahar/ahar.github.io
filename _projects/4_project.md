---
layout: page
title: Localizability-Aware Fail-Safe Localization
description: R&D lead for a novel localizability estimation module enabling robust multi-modal localization in dynamic indoor environments.
img: assets/img/localizability_map.png
importance: 2
category: industry
---

## Problem

A visually appealing map does not guarantee reliable localization everywhere within it. Scene dynamism, sensor quality, and local geometry all affect localization confidence — yet ground truth is rarely available at runtime in deployed AMRs.

## Approach

I led R&D for a **localizability estimation** module as part of a fault-tolerant localization provider for GPS-denied natural navigation:

- Real-time assessment of **localization quality** from local geometric structure
- Guides judicious fusion of **visual, LiDAR, and IMU** odometry streams
- Combined with **map quality estimation** (RGB-D and LiDAR maps)
- Architecture owner for the full fail-safe localization project across warehouses, manufacturing sites, hospitals, and malls

## Results

- Novel localizability module found **highly effective** for GPS-denied natural navigation
- Enables proactive modality switching before localization failure
- Supports continuous operation under diverse scene dynamism and surface conditions

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.html path="assets/img/localizability_map.png" title="Localizability map" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Localizability estimation identifies regions where localization is reliable vs. degenerate, enabling adaptive sensor fusion.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/inlier_outlier.png" title="Inlier and outlier points" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.html path="assets/img/refined_surfel.png" title="Surface normal estimation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Outlier-robust plane fitting and normal estimation support geometry-aware localizability analysis.
</div>

## Technologies

ROS 2 · Multi-modal odometry · Map quality estimation · Point cloud geometry · Sensor fusion
