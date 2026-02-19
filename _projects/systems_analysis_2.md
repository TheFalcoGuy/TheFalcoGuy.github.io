---
title: "Investigating the feasibility of SuperLimbs in a partial-gravity environment"
layout: single
order: 2
excerpt: " "
publication_gallery:
  - image_path: /assets/images/Logos/ICRA_2024_Logo.jpg
    alt: "ICRA 2024 Logo"
  - image_path: /assets/images/Logos/SCITECH_FORUM_Logo.png
    alt: "Scitech Logo"
---

## Overview

This study proposes the utilization of Supernumerary Robotic Limbs (SuperLimbs) for augmenting astronauts during an Extra-Vehicular Activity (EVA) in a partial-gravity environment. We investigate the effectiveness of SuperLimbs in assisting astronauts to their feet following a fall. 

Based on preliminary observations from a pilot human study, we categorized post-fall recoveries into a sequence of statically stable poses called "waypoints". The paths between the waypoints can be modeled with a simplified kinetic motion applied about a specific point on the body. Following the characterization of post-fall recoveries, we designed a task-space impedance control with high damping and low stiffness, where the SuperLimbs provide an astronaut with assistance in post-fall recovery while keeping the human-in-the-loop scheme. 

In order to validate this control scheme, a full-scale wearable analog space suit was constructed and tested with a SuperLimbs prototype. Results from the experimentation found that without assistance, astronauts would impulsively exert themselves to perform a post-fall recovery, which resulted in high energy consumption and instabilities maintaining an upright posture, concurring with prior NASA studies. When the SuperLimbs provided assistance, the astronaut’s energy consumption and deviation in their tracking as they performed a post-fall recovery was reduced considerably.

## Relevant Publications

{% include gallery id="publication_gallery" layout="half" class="align-center" %}

1. **Ballesteros, E.**, Lee, S.-Y., Carpenter, K., & Asada, H. H. (2024). Supernumerary Robotic Limbs to Support Post-Fall Recoveries for Astronauts. *2024 IEEE International Conference on Robotics and Automation (ICRA)*, 2324-2331. https://doi.org/10.1109/ICRA57147.2024.10610849 [[PDF]](/assets/papers/ICRA_2024.pdf){:target="_blank"} [[Video]](https://www.youtube.com/watch?v=4poNOVQjxEg){:target="_blank"}

2. **Ballesteros, E.**, Carpenter, K., & Asada, H. H. (2025). Supernumerary Robotic Limbs to Augment Astronauts Performing Post-Fall Recoveries during Partial-Gravity Spacewalks. *2025 AIAA SCITECH Forum*. https://doi.org/10.2514/6.2025-1191 [[PDF]](/assets/papers/Scitech_2025.pdf){:target="_blank"}

## Conference Poster

<iframe src="/assets/images/ICRA_2024/ICRA_2024_Poster.pdf" width="100%" height="600px" style="border: none;"></iframe>

## Video Demo (Preliminary Human Testing)

<iframe width="560" height="315"
src="https://www.youtube.com/embed/4poNOVQjxEg"
frameborder="0"
allowfullscreen></iframe>

## Video Demo (Control Tuning for Augmentation)

<iframe width="560" height="315"
src="https://www.youtube.com/embed/wED3lBVopq4"
frameborder="0"
allowfullscreen></iframe>