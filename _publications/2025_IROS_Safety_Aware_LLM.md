---
title: "Safety Aware Task Planning via Large Language Models in Robotics"
collection: publications
category: conferences
permalink: /publication/2025_IROS_Safety_Aware_LLM
excerpt: 'Design of a multi agent arquitecture to plan a task sequence given a series of robot capabilities and then check for safety considerations to define control constraints and task sequence safety violations'
date: 2025-10-19
venue: 'IEEE International Conference on Robotics and Automation (ICRA)'
#slidesurl: 'https://academicpages.github.io/files/slides2.pdf'
paperurl: 'https://sfaguile-uc.github.io/files/2025_IROS_Safety_Aware_LLM.pdf'
bibtexurl: 'https://sfaguile-uc.github.io/files/2025_IROS_Safety_Aware_LLM.bib'
citation: 'A. A. Khan et al., "Safety Aware Task Planning via Large Language Models in Robotics", 2025 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), Hangzhou, China, 2025, pp. 21024-21031, doi: 10.1109/IROS60139.2025.11246041.'
---

The integration of large language models (LLMs) into robotic task planning has unlocked better reasoning capabilities for complex, long-horizon workflows. However, ensuring safety in LLM-driven plans remains a critical challenge, as these models often prioritize task completion over risk mitigation. This paper introduces SAFER (Safety-Aware Framework for Execution in Robotics), a multi-LLM framework designed to embed safety awareness into robotic task planning. SAFER employs a Safety Agent that operates alongside the primary task planner, providing safety feedback. Additionally, we introduce LLM-as-a-Judge, a novel metric leveraging LLMs as evaluators to quantify safety violations within generated task plans. Our framework integrates safety feedback at multiple stages of execution, enabling real-time risk assessment, proactive error correction, and transparent safety evaluation. We also integrate a control framework using Control Barrier Functions (CBFs) to ensure safety guarantees within SAFER’s task planning. We evaluated SAFER against state-of-the-art LLM planners on complex long-horizon tasks involving heterogeneous robotic agents, demonstrating its effectiveness in reducing safety violations while maintaining task efficiency. We also verify the task planner and safety planner through actual hardware experiments involving multiple robots and a human.