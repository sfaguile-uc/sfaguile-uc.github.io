---
title: "Modeling and Inertial Parameter Estimation of Cart-like Nonholonomic Systems Using a Mobile Manipulator"
collection: publications
category: conferences
permalink: /publication/2023_ICRA_Modeling_and_Parameter_Estimation
excerpt: 'Using a torque controlled manipulator we estimate inertial parameters (mass, center of mass and inertia) of a nonholonomic systems using an extender Kalman filter. We validate the approach using hardware experiments using mobile manipulators.'
date: 2023-05-29
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2023_ICRA_Modeling_and_Parameter_Estimation.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2023_ICRA_Modeling_and_Parameter_Estimation.bib'
citation: 'S. Aguilera, M. A. Murtaza, J. Rogers and S. Hutchinson, "Modeling and Inertial Parameter Estimation of Cart-like Nonholonomic Systems Using a Mobile Manipulator", 2023 IEEE International Conference on Robotics and Automation (ICRA), London, United Kingdom, 2023, pp. 3073-3079, doi: 10.1109/ICRA48891.2023.10161076.'
---

To enable a mobile manipulator to effectively maneuver a cart, we derive a dynamic model for the cart that incorporates the nonholonomic constraints on its motion, and use this model to formulate an estimator for the cart's inertial parameters. By deriving the dynamic equations of the cart using a constrained Euler-Lagrange formulation, we are able to directly incorporate nonholonomic constraints into the dynamics in a way that is independent of the kinematic parameters of the cart (e.g., specific wheel configuration, wheel radius, etc.), eliminating the need to either calibrate or estimate these kinematic parameters. We then construct an extended Kalman filter (including an explicit calculation of the linearized system and observation matrices) that uses an augmented state representation to estimate the cart's inertial parameters. We validate our approach both in simulation and experimentally using a mobile manipulator to maneuver a typical shopping cart. These experiments confirm the accuracy of our estimator, show that accurate estimation of the inertial parameters can significantly reduce the force/torque needed to successfully control the system, and illuminate the effects of varying the contact points at which the mobile manipulator applies forces and torques to guide the cart along a desired trajectory.