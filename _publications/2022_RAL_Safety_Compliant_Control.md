---
title: "Safety Compliant Control for Robotic Manipulator With Task and Input Constraints"
collection: publications
category: manuscripts
permalink: /publication/2022_RAL_Safety_Compliant_Control
excerpt: 'CBF and RESCLF torque controllers in operational space to dynamically adapt to robot constraints. Evaluated with real hardware experiments.'
date: 2022-05-30
venue: 'IEEE Robotics and Automation Letters'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2022_RAL_Safety_Compliant_Control.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2022_RAL_Safety_Compliant_Control.bib'
citation: 'M. A. Murtaza, S. Aguilera, M. Waqas and S. Hutchinson, "Safety Compliant Control for Robotic Manipulator With Task and Input Constraints," in IEEE Robotics and Automation Letters, vol. 7, no. 4, pp. 10659-10664, Oct. 2022, doi: 10.1109/LRA.2022.3179118.'
---

Increasingly, robots are working in close proximity with humans, and in dynamically changing environments. We present a new control architecture that guarantees safety under such conditions, while simultaneously ensuring that task goals are satisfied. Our approach combines Control Barrier Functions (to provide safety guarantees) with Rapidly Exponentially Stabilizing Control Lyapunov functions (to satisfy task constraints and ensure exponential convergence). We formulate the problem completely in the operational space, using super ellipsoids to define safe sets which are dynamically adapted to restrict the robot’s operational space in response to moving obstacles (including humans). Control barrier functions, which can be implemented in real time using quadratic programming, ensure the forward invariance of these safe sets, while minimally perturbing prescribed control trajectories. We demonstrate our approach on a seven degree-of-freedom Kuka LBR iiwa robotic manipulator, both in a physics engine-based simulation and with real hardware experiments.