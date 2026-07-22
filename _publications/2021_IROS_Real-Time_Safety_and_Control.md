---
title: "Real-Time Safety and Control of Robotic Manipulators with Torque Saturation in Operational Space"
collection: publications
category: conferences
permalink: /publication/2021_IROS_Real-Time_Safety_and_Control
excerpt: 'Control Barrier Functions (CBF) and Rapidly Exponentially Stabilizing Control Lyapunov Functions (RESCLF) to ensure safety for torque controlled manipulators'
date: 2021-09-27
venue: ' IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2021_IROS_Real-Time_Safety_and_Control.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2021_IROS_Real-Time_Safety_and_Control.bib'
citation: 'M. A. Murtaza, S. Aguilera, V. Azimi and S. Hutchinson, "Real-Time Safety and Control of Robotic Manipulators with Torque Saturation in Operational Space," 2021 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Prague, Czech Republic, 2021, pp. 702-708, doi: 10.1109/IROS51168.2021.9636794.'
---

This paper presents a real-time safety and control for robot manipulators using control barrier functions and control Lyapunov functions in operational space. We first define the operational space in terms of system dynamics, jacobian, and torques and then ensure safety by designing Control Barrier Functions (CBF) around the body links of the robotic manipulator. The control barrier function provides provable collision-free behavior for the robotic manipulator by modifying the nominal control in a minimally invasive manner to formally satisfy the safety constraints. CBFs are formulated as a quadratic programming problem, which can be solved in real-time. We also design a controller based on Rapidly Exponentially Stabilizing Control Lyapunov Function (RESCLF) and quadratic programming to meet multiple objectives while ensuring exponential convergence. We then extend our formulation to solve RESCLF and CBF in a unified formulation to design the controller while ensuring the safety of manipulators and guaranteeing the torque saturation. The efficacy of the proposed approach is shown on 7 Degree of Freedom (DoF) KUKA LBR iiwa robot using Dynamic Animation and Robotics Toolkit (DART) physics engine.