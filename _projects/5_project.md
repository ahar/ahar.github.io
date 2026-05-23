---
layout: page
title: Visual-Inertial Odometry
description: 15-DoF VIO state estimation and research on DNN-based stable visual-inertial odometry for dynamic indoor environments.
img: assets/img/vio_setup.jpg
importance: 3
category: industry
---

## Problem

Classical visual-inertial odometry suffers from sudden covariance surges in dynamic, feature-poor indoor environments — limiting its use as a reliable odometry source for autonomous mobile robots.

## Approach

My team and I developed a **15-DoF state estimation model** for stable VIO with dominant bias compensation. I am extending this with a **DNN-based stable VIO** technique that:

- Learns **IMU features** and fuses them with visual features
- Uses **hardware time synchronization** between IMU and camera
- Alleviates sudden surges in VIO covariance estimates from classical methods
- Enables seamless switching from feature-based navigation to VIO when visual features are insufficient

## Results

- Stable VIO pipeline integrated into production navigation stack
- Research direction bridging classical state estimation and learning-enhanced odometry
- Supports autonomous operation in large dynamic indoor facilities

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.html path="assets/img/vio_setup.jpg" title="VIO experimental setup" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Visual-inertial odometry experimental setup for indoor AMR navigation.
</div>

## Technologies

ROS 2 · VIO · IMU · Camera · PyTorch · State estimation · Sensor synchronization
