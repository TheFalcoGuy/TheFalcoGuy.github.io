---
title: "Design of the first functional SuperLimbs prototype: The SuperLimbs-T1.0"
layout: single
order: 3
excerpt: " "
publication_gallery:
  - image_path: /assets/images/Logos/ICRA_2026_Logo.png
    alt: "ICRA 2026 Logo"
  - image_path: /assets/images/Logos/IJRR_Logo.png
    alt: "Scitech Logo"
---

## Overview

This article presents a methodology for the design of a pair of wearable robotic appendages, known as Supernumerary Robotic Limbs, or SuperLimbs for short. Specifically, we aim to design SuperLimbs for assisting astronauts while they perform partial-gravity Extra-Vehicular Activities (EVAs) on the Moon. NASA has identified recovering from a fall as a high-risk process needing an effective countermeasure. 

Preliminary human study data discovered uniform behavior in astronaut's poses as they performed a post-fall recovery wearing a space suit assembly. Based on this observation, this paper presents a complementary biomechanical model which estimates the torques required by an astronaut to navigate their body through a post-fall recovery. By comparing maximum allowable joint torques of the astronaut with the required joint torques, we identify the gap that SuperLimbs must fill by exerting necessary forces along a desired trajectory. 

A parametric optimization problem is formulated for designing SuperLimbs that meet these requirements with least energy consumption. A two-phase design optimization method is developed. 

- Phase 1 consists of utilizing a coarse-grid AI searcher that rules out invalid designs that do not meet basic functional requirements. 
- Phase 2 uses the optimal permutation from Phase 1 as an initial estimate for a fine-grid parameter-sweep optimization where energy dissipation across the actuators and task-space tracking accuracy are used as performance metrics. 

Based on the optimal design, an Earth-based prototype is built in-house at the NASA Jet Propulsion Laboratory, and its feasibility for astronaut’s fall recovery assistance is evaluated. 

## Relevant Publications

{% include gallery id="publication_gallery" layout="half" class="align-center" %}

1. **Ballesteros, E.**, Rogers, P., Jenkins, J., Carpenter, K., & Asada, H. H., "Design of Supernumerary Robotic Limbs for the Augmentation of Astronauts performing Partial-Gravity Extra-Vehicular Activities (EVAs)," *International Journal of Robotics Research (IJRR)*, 2026.

## Conference Poster

## Video Demo

<iframe width="560" height="315"
src="https://www.youtube.com/embed/byLhhDbOsq4"
frameborder="0"
allowfullscreen></iframe>