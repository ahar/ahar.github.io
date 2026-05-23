---
layout: page
title: RBLAM — Reflector-Based Localization
description: Sole inventor of production-grade reflector-based localization and mapping, deployed at industrial customer sites.
img: assets/img/localizability_map.png
importance: 1
category: industry
---

## Problem

Large industrial facilities (warehouses, manufacturing plants) pose severe challenges for visual and LiDAR SLAM — repetitive structure, scene dynamism, and map scale cause localization failures in GPS-denied natural navigation systems.

## Approach

I invented **RBLAM (Reflector-Based Localization and Mapping)** and led its production-grade development:

- Sparse **reflector-landmark** representation with **probabilistic data association**
- Integration into the production navigation stack with online map management
- Fail-over logic for continuous operation when primary localization modalities degrade
- Related patent filed — *A Mobile Entity Localization System and a Method Thereof*

## Results

- **Sole inventor** and technical lead for algorithm and deployment
- Deployed at **2+ customer sites** in industrial environments
- Enables robust relocalization where feature-based methods struggle
- Complements natural navigation with a dedicated sparse-landmark modality

## Technologies

ROS 2 · C++ · GTSAM · LiDAR · Probabilistic estimation · Map management
