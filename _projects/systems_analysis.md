---
title: "Investigating the feasibility of SuperLimbs in a micro-gravity environment"
layout: single
order: 1
excerpt: "Improving ergonomics during ISS EVAs"

publication_gallery:
  - image_path: /assets/images/Logos/ICRA_2023_Logo.png
    alt: "ICRA 2023 Logo"
  - image_path: /assets/images/Logos/CHI_2022_Logo.png
    alt: "CHI 2022 Logo"

test_gallery:
  - image_path: /assets/images/ICRA_2023/Test_1.jpeg
    alt: "Test 1"
  - image_path: /assets/images/ICRA_2023/Test_2.jpeg
    alt: "Test 2"

results_deflection_gallery:
  - image_path: /assets/images/ICRA_2023/Deflection.PNG
    alt: "X Direction Deflection"
    caption: "Deflection of astronaut CoM under applied load in X direction"
  - image_path: /assets/images/ICRA_2023/Deflection_y_axis.PNG
    alt: "Y Direction Deflection"
    caption: "Deflection of astronaut CoM under applied load in Y direction"
  - image_path: /assets/images/ICRA_2023/Deflection_z_axis.PNG
    alt: "Z Direction Deflection"
    caption: "Deflection of astronaut CoM under applied load in Z direction"
---

## Overview

Beginning this project, we investigate the impact of using SuperLimbs in an immediate use-case for astronauts: EVAs on the International Space Station (ISS).

*With SuperLimbs, we can reduce EVA fatigue by nearly 50% and expand reach by 1 m^2.*

## Problem Approach

During an EVA onboard the ISS, astronauts expend a significant amount of oxygen reserves performing "transfer operations", in which they move from one worksite to another. This is due to the fact that astronauts must move fight against the stiffness of their pressurized space suit to grab handrails and propel their bodies. 

<div style="text-align: center;">
  <video width="560" height="315" controls>
    <source src="/assets/videos/NBL_Short.mp4" type="video/mp4">
  </video>
  <figcaption>Transfer operation expected from ISS EVAs (Neutral Buoyancy Laboratory analog)</figcaption>
</div>

In addition to poor ergonomics during transfer operations, astronauts must also brace their body while they are at a worksite. Astronauts must use one of their arms (or tying their legs to a rigid structure) to brace their bodies, leading to poor worksite ergonomics.

With a set of SuperLimbs, 

- **An astronaut operator can be statically braced** against the ISS with full use of their arms and legs
- **An astronaut can intuitively command the SuperLimbs** by pulling along the direction the astronaut wants to move. The SuperLimbs can interpret the reaction load as a command input and begin walking the astronaut/SuperLimbs system in that direction.
- **The working envelope of the astronaut is greatly expanded**, as the SuperLimbs can reconfigure the astronaut's body over a worksite. The SuperLimbs' dextrous range becomes the astronaut's working envelope.

## Key Results

**An astronaut operator can be statically braced**
An experiment was conducted where a mannequin, rigidly fixed to a set of Universal Robots UR5e cobots was pushed alongside a mockup of the exterior of the ISS. The UR5es acted as a set of SuperLimbs, having the end-effectors grip high-fidelity handrails on the ISS mockup.

{% include gallery id="test_gallery" layout="half" class="align-center" %}

<div style="display: flex; justify-content: center; align-items: flex-end; gap: 10px; margin-top: 20px;">
  <figure style="text-align: center; margin: 0; flex: 1;">
    <img src="/assets/images/ICRA_2023/Deflection.PNG" alt="X Direction Deflection" style="width: 100%; height: 250px; object-fit: contain;">
    <figcaption>X direction</figcaption>
  </figure>
  <figure style="text-align: center; margin: 0; flex: 1;">
    <img src="/assets/images/ICRA_2023/Deflection_y_axis.PNG" alt="Y Direction Deflection" style="width: 100%; height: 250px; object-fit: contain;">
    <figcaption>Y direction</figcaption>
  </figure>
  <figure style="text-align: center; margin: 0; flex: 1;">
    <img src="/assets/images/ICRA_2023/Deflection_z_axis.PNG" alt="Z Direction Deflection" style="width: 100%; height: 250px; object-fit: contain;">
    <figcaption>Z direction</figcaption>
  </figure>
</div>

*Deflection reduced by < 5mm under 89N load*

**An astronaut can intuitively command the SuperLimbs**
When the SuperLimbs are attached to the exterior of the ISS, they form a closed-loop kinematic chain with the astronaut wearer. Using admittance control, an intuitive command interface was made that allows the astronaut to seamlessly command the SuperLimbs to shift their position.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px;">
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <video width="100%" controls>
      <source src="/assets/videos/Micro_Gravity_Test.MOV" type="video/quicktime">
    </video>
    <figcaption>Demonstration of reaction-load from astronaut as command input (admittance control)</figcaption>
  </figure>
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <img src="/assets/images/ICRA_2023/Power_Output_Attenuation.PNG" alt="Power Output" style="max-width: 100%; height: auto;">
    <figcaption>Energy required from astronaut to command the SuperLimbs</figcaption>
  </figure>
</div>

*Power reduced from performing transfer operation by approximately 50%*

**The working envelope of the astronaut is greatly expanded**
Analysis of the workspace of the combined dual-UR5e system provided apples-to-apples comparisons with an astronaut's current working envelope onboard the ISS. Overlapping of the workspaces between the two UR5e manipulators provides the expanded working envelope provided to astronauts.

<div style="display: flex; justify-content: center; align-items: flex-start; gap: 20px;">
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <video width="100%" controls>
      <source src="/assets/videos/Workspace_Analysis.mp4" type="video/mp4">
    </video>
    <figcaption>Expanded workspace analysis gained by use of SuperLimbs</figcaption>
  </figure>
  <figure style="text-align: center; margin: 0; flex: 1; max-width: 45%;">
    <img src="/assets/images/ICRA_2023/Allowable_Workspace_Human_CoM_Highlighted.png" alt="Workspace diagram" style="max-width: 100%; height: auto;">
    <figcaption>Expanded workspace by overlapping UR5e workspaces</figcaption>
  </figure>
</div>

*Working envelope expanded by approximately 1 m^2*

## Next Steps

Now that SuperLimbs has been demonstrated in a testbed setting to be beneficial to astronauts, efforts must shift towards enabling the technology for *partial-gravity EVAs*, where future Artemis missions will require significant workload tasks from suited astronauts.

[Continue to Partial-Gravity Study →](/projects/systems-analysis-2/)

**This study elevates the technology from TRL 1 to TRL 2**

## Relevant Publications

{% include gallery id="publication_gallery" layout="half" class="align-center" %}

1. **Ballesteros, E.** & Asada, H. H. (2022). Integrating Supernumerary Robotic Limbs onto the xEMU spacesuit to enhance astronaut capabilities and efficiency in Extra-Vehicular Activities. *2022 ACM Conference on Human Interaction (SpaceCHI2.0)*, 2022. [[PDF]](/assets/papers/ACM_SpaceCHI2.0_2022.pdf)

2. **Ballesteros, E.**, Man, B., & Asada, H. H. (2023). Supernumerary Robotic Limbs for Next Generation Space Suit Technology. *2023 IEEE International Conference on Robotics and Automation (ICRA)*, 7519-7525. https://doi.org/10.1108/ICRA48891.2023.10161579 [[PDF]](/assets/papers/ICRA_2023.pdf){:target="_blank"} [[Video]](https://youtube.com/watch?v=Wed7JAyfLyA){:target="_blank"}

3. Asada, H. H., & **Ballesteros, E.** (2023). Systems and Methods for Assisting Movement using Robotic Limbs (Patent No. WO 2023/212212 A2). World Intellectual Property Organization.

## Conference Poster

<iframe src="/assets/images/ICRA_2023/ICRA_2023_Poster.pdf" width="100%" height="600px" style="border: none;"></iframe>

## Video Demo

<div style="text-align: center;">
  <iframe width="560" height="315"
  src="https://www.youtube.com/embed/Wed7JAyfLyA"
  frameborder="0"
  allowfullscreen></iframe>
</div>