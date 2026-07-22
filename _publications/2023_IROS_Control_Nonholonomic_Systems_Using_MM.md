---
title: "Control of Cart-Like Nonholonomic Systems Using a Mobile Manipulator"
collection: publications
category: manuscripts
permalink: /publication/2023_IROS_Control_Nonholonomic_Systems_Using_MM
excerpt: 'Using of torque controller to manipulated nonholonomic system using a mobile manipulator with hardware experimentation.'
date: 2023-10-01
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2023_IROS_Control_Nonholonomic_Systems_Using_MM.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2023_IROS_Control_Nonholonomic_Systems_Using_MM.bib'
citation: 'S. Aguilera and S. Hutchinson, "Control of Cart-Like Nonholonomic Systems Using a Mobile Manipulator," 2023 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Detroit, MI, USA, 2023, pp. 6801-6808, doi: 10.1109/IROS55552.2023.10342088.'
---

This work focuses on the capability of Mobile Manipulators to effectively control and maneuver cart-like non-holonomic systems. These cart-like systems are passive-wheeled objects with nonholonomic constraints with varying inertial parameters. We derive the dynamic equations of the cart-like system using a constrained Euler-Lagrange formulation and propose a Linear Quadratic Regulator controller to move the cart along a desired trajectory using external forces (applied by the MM) at a given contact point. For the MM, we present a control architecture to i) control the mobile base to keep the cart inside the workspace of the manipulator and ii) a control Lyapunov function formulation to control the manipulator in torque control, while decoupling the motion of the base from the arm and applying the required wrench onto the object. We validate our approach experimentally, using a MM to push a shopping cart and track desired trajectories. These experiments show the accuracy of the control architecture to track the desired trajectories for carts with different inertial parameters and improve the controllability of the system by changing the contact point on the cart.