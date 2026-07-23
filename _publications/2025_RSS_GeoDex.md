---
title: "GeoDEx: A Unified Geometric Framework for Tactile Dexterous and Extrinsic Manipulation under Force Uncertainty"
collection: publications
category: conferences
permalink: /publication/2025_RSS_GeoDex
excerpt: 'Use of tactile sensor in multi-finger robotic hand to accomplished estimation, planning and control of objects based on noisy force readings.'
date: 2025-06-23
venue: 'Robotics: Science and Systems XXI'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2025_RSS_GeoDex.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2025_RSS_GeoDex.bib'
citation: 'S. Chen, S. Aguilera, S. Iba, and R. Soltani-Zarrin, "GeoDEx: A Unified Geometric Framework for Tactile Dexterous and Extrinsic Manipulation under Force Uncertainty", 2025 Proceedings of Robotics: Science and Systems (RSS), Los Angeles, California, USA, 2025, doi: 10.15607/RSS.2025.XXI.057.'
---

Sense of touch that allows robots to detect contact and measure interaction forces enables them to perform challenging tasks such as grasping fragile objects or using tools. Tactile sensors in theory can equip the robots with such capabilities. However, accuracy of the measured forces is not on a par with those of the force sensors due to the potential calibration challenges and noise. This has limited the values these sensors can offer in manipulation applications that require force control. In this paper, we introduce GeoDEx, a unified estimation, planning, and control framework using geometric primitives such as plane, cone and ellipsoid, which enables dexterous as well as extrinsic manipulation in the presence of uncertain force readings. Through various experimental results, we show that while relying on direct inaccurate and noisy force readings from tactile sensors results in unstable or failed manipulation, our method enables successful grasping and extrinsic manipulation of different objects. Additionally, compared to directly running optimization using SOCP (Second Order Cone Programming), planning and force estimation using our framework achieves a 14x speed-up.