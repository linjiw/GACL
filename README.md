# Grounded Adaptive Curriculum Learning (GACL)

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)

GACL is an open-source plug-in module designed to advance curriculum learning in complex robotic tasks. Our framework addresses the limitations of manually designed curricula by providing an automated, adaptive solution that scales to the demands of real-world robotics.
<p align="center">
  <img src="figures/GACL illustration.pdf" alt="GACL Framework Illustration" width="800"/>
</p>

## Overview

Curriculum learning has emerged as a promising approach for training complex robotics tasks, yet existing methods often rely on hand-crafted curricula that require extensive engineering and may suffer from subjective, suboptimal choices. GACL introduces three key innovations:

- **Task Representation:** A robust method to consistently handle the design of complex robot tasks.
- **Active Performance Tracking:** An adaptive mechanism that tailors curriculum generation to the robot’s current capabilities.
- **Grounding Mechanism:** An approach that alternates between reference and synthetic tasks, ensuring relevance to target domain distributions.
<p align="center">
  <img src="figures/gacl method.pdf" alt="GACL Method" width="700"/>
</p>

## Features

- **Plug-in Module:** Seamlessly integrate GACL with your existing robotics frameworks.
- **Open Source:** We are committed to transparency and collaboration in the robotics community.
- **Adaptive Curriculum Learning:** Automatically generate curricula that evolve with the robot’s performance.
- **Scalability:** Efficiently manage complex task spaces with minimal manual intervention.
- **Grounded Relevance:** Maintain alignment with real-world task distributions.


## Results
Our experiments demonstrate that GACL significantly improves learning efficiency and performance in complex robotic tasks:
<p align="center">
  <img src="figures/curriculum_progression.pdf" alt="Curriculum Progression" width="600"/>
</p>
<p align="center">
  <img src="figures/GACL curriculum difficulty progression results.pdf" alt="GACL Curriculum Difficulty Progression Results" width="700"/>
</p>
