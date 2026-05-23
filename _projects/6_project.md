---
layout: page
title: Feature SLAM & Map Management
description: Feature-based SLAM with online map switching and AdaBoost loop closure for ultra-large dynamic environments.
img: assets/img/12.jpg
importance: 4
category: industry
---

## Problem

Ultra-large warehouses and manufacturing sites exceed the memory and compute budget of resource-constrained edge computers when loading monolithic maps. Dynamic environments further degrade loop closure reliability.

## Approach

I led the mapping team toward a production **feature-based SLAM** product with two key contributions:

**Online map switching**
- Divides large environments into small map chunks
- Loads chunks on demand based on navigation requirements
- Avoids loading entire facility maps on resource-constrained host computers

**Robust loop closure detection**
- **AdaBoost classifier**-based loop closure model robust to environmental changes
- Integrated with range-based and feature-based SLAM implementations
- First major project at Novus Hi-Tech (NHRSL)

## Results

- Enabled SLAM-based navigation in ultra-large industrial facilities
- Map switching critical for scalable deployment across multi-site customers
- Loop closure robustness improved under environmental change and dynamism

## Technologies

ROS 2 · Feature-based SLAM · Loop closure · Map management · AdaBoost · Edge computing
