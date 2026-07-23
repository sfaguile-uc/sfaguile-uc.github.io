---
title: "Multi-Finger Manipulation via Trajectory Optimization With Differentiable Rolling and Geometric Constraints"
collection: publications
category: manuscripts
permalink: /publication/2025_RAL_Multi-Finger_Manipulation
excerpt: 'Using a Signed Distance Field (SDF) sampling method to estimate contact for traejctory optimization for multi-finger dexterous manipualtion'
date: 2025-04-03
venue: 'IEEE Robotics and Automation Letters'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2025_RAL_Multi-Finger_Manipulation.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2025_RAL_Multi-Finger_Manipulation.bib'
citation: 'F. Yang, T. Power, S. A. Marinovic, S. Iba, R. S. Zarrin and D. Berenson, "Multi-Finger Manipulation via Trajectory Optimization With Differentiable Rolling and Geometric Constraints", in IEEE Robotics and Automation Letters, vol. 10, no. 5, pp. 5170-5177, May 2025, doi: 10.1109/LRA.2025.3557752.'
---

Parameterizing finger rolling and finger-object contacts in a differentiable manner is important for formulating dexterous manipulation as a trajectory optimization problem. In contrast to previous methods which often assume simplified geometries of the robot and object or do not explicitly model finger rolling, we propose a method to further extend the capabilities of dexterous manipulation by accounting for non-trivial geometries of both the robot and the object. By integrating the object's Signed Distance Field (SDF) with a sampling method, our method estimates contact and rolling-related variables in a differentiable manner and includes those in a trajectory optimization framework. This formulation naturally allows for the emergence of finger-rolling behaviors, enabling the robot to locally adjust the contact points. To evaluate our method, we introduce a benchmark featuring challenging multi-finger dexterous manipulation tasks, such as screwdriver turning and in-hand reorientation. Our method outperforms baselines in terms of achieving desired object configurations and avoiding dropping the object. We also successfully apply our method to a real-world screwdriver turning task and a cuboid alignment task, demonstrating its robustness to the sim2real gap.