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
superemu_gallery:
  - image_path: /assets/images/ICRA_2024/SuperEMU_1.JPG
    alt: "SuperEMU 1"
  - image_path: /assets/images/ICRA_2024/SuperEMU_2.JPG
    alt: "SuperEMU 2"
  - image_path: /assets/images/ICRA_2024/SuperEMU_3.JPG
    alt: "SuperEMU 3"
  - image_path: /assets/images/ICRA_2024/SuperEMU_4.JPG
    alt: "SuperEMU 4"
---

## Overview

Aligning with NASA's priorities (surface-based EVAs), we investigate the use case of using SuperLimbs in a Lunar/Martian use-case.

*With SuperLimbs, we can aid astronauts recover safety from a fall 100% of the time.*

## Problem Approach

During an EVA on the surface of an extraterrestrial surface, such as the moon or Mars, astronauts are faced with several risks. Surface-based risks are associated with an unstructured surface and a lack of control/versatility with a pressurized space suit.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px;">
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <video width="100%" controls>
      <source src="/assets/videos/xEMU_1.MOV" type="video/quicktime">
    </video>
    <figcaption>xEMU Space Suit performing lifting operation</figcaption>
  </figure>
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <video width="100%" controls>
      <source src="/assets/videos/xEMU_2.MOV" type="video/quicktime">
    </video>
    <figcaption>xEMU Space Suit performing traversal operation</figcaption>
  </figure>
</div>

Astronauts, being expected to take on several construction-like tasks (such as constructing nuclear power plants or data centers on the moon) will be subjected to work-related injuries due to poor ergonomics. Additionally, astronauts can easily fall on the surface, leading to potentially catastrophic conditions. 

With a set of SuperLimbs,

- **An astronaut can safely recover from a fall** without a need to overexert themselves to stand back up

- **An astronaut's stability can be improved** while performing strenous tasks

- **An astronaut's fall can be detected early** and allow the SuperLimbs to arrest the fall, leading to less dangerous fall conditions

## Key Results

*Due to the scope of this effort, we will focus on investigation of recovering from a fall, as that is the most prevalent and urgent risk that NASA has identified to mitigate. The latter two features from SuperLimbs will be investigated at a later stage in the project.*

**An astronaut can safely recover from a fall**
A preliminary human experiment was conducted that profiled the trajectories taken when asked to stand from a prone or supine position. The control condition asked subjects to stand up while wearing comfortable workout clothes. A partial constrained condition, where medical bandages wrapped around their joints were added to simulate pressurized space suit stiffness. A fully constrained condition, where subjects would wear the SuperEMU, which simulates the xEMU Hard Upper Torso (HUT). 

{% include gallery id="superemu_gallery" layout="half" %}

From these experiments, the following key observations were made:

1. When unconstrained, humans take a variety of paths to stand up. The type of trajectory taken is largely random and cannot be accurately predicted/anticipated. However, between all human subjects, priority was given to efficiency over stability.

2. When partially constrained, the sample population began to show signs of adopting a more uniform trajectory to standing up. Particularly, their motions remained largely within the sagittal plane, prioritizing stability over efficiency.

3. When wearing a space suit, the sample population all took the same uniform trajectory that was noticed during the partially constrained case, showing that astronauts, under unique loads from the space suit, take a conservative and predictable trajectory.



## Next Steps

## Relevant Publications

{% include gallery id="publication_gallery" layout="half" class="align-center" %}

1. **Ballesteros, E.**, Lee, S.-Y., Carpenter, K., & Asada, H. H. (2024). Supernumerary Robotic Limbs to Support Post-Fall Recoveries for Astronauts. *2024 IEEE International Conference on Robotics and Automation (ICRA)*, 2324-2331. https://doi.org/10.1109/ICRA57147.2024.10610849 [[PDF]](/assets/papers/ICRA_2024.pdf){:target="_blank"} [[Video]](https://www.youtube.com/watch?v=4poNOVQjxEg){:target="_blank"}

2. **Ballesteros, E.**, Carpenter, K., & Asada, H. H. (2025). Supernumerary Robotic Limbs to Augment Astronauts Performing Post-Fall Recoveries during Partial-Gravity Spacewalks. *2025 AIAA SCITECH Forum*. https://doi.org/10.2514/6.2025-1191 [[PDF]](/assets/papers/Scitech_2025.pdf){:target="_blank"}

## Conference Poster

<iframe src="/assets/images/ICRA_2024/ICRA_2024_Poster.pdf" width="100%" height="600px" style="border: none;"></iframe>

## Video Demo (Preliminary Human Testing)

<div style="text-align: center;">
  <iframe width="560" height="315"
  src="https://www.youtube.com/embed/4poNOVQjxEg"
  frameborder="0"
  allowfullscreen></iframe>
</div>

## Video Demo (Control Tuning for Augmentation)

<div style="text-align: center;">
  <iframe width="560" height="315"
  src="https://www.youtube.com/embed/wED3lBVopq4"
  frameborder="0"
  allowfullscreen></iframe>
</div>