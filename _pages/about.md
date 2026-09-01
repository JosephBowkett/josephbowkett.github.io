---
permalink: /
title: "About & Research"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am the **Group Lead for Robotic Manipulation & Sampling** within the Robotic Mobility & Manipulation section of NASA's Jet Propulsion Laboratory (JPL), and a Caltech alumnus (Ph.D. in Mechanical Engineering, Burdick Robotics Lab). 

My work bridges **hands-on robotics systems engineering** and **technical leadership**. As an active individual contributor and architect, I develop, integrate, and deploy autonomy, real-time control, contact-rich manipulation, high-DoF locomotion, and embedded compute across physical robot platforms. As a Group Lead and Task Manager, I mentor engineers and research interns, guide architectural strategy, and partner across industry and spaceflight ecosystems to transition advanced autonomy from concept to flight and field demonstration.

Below are highlights of recent research, mission capabilities, and robotic systems development:

---

### Robot Learning, Simulation & Edge AI

#### NVIDIA Isaac Lab & Learning-Based Locomotion
Served as technical mentor for development of PPO locomotion policies trained in **NVIDIA Isaac Lab** for an 18-DoF three-legged wheel-on-limb robot navigating challenging, irregular terrain. Supported the team from policy-training architecture through model export and target-platform inference, connecting simulation-trained RL policies to embedded deployment.

#### Vision-Language-Action (VLA) Manipulation Research
Actively mentoring an intern research initiative investigating Vision-Language-Action (VLA) foundation models to enhance generalized, perception-guided dexterous manipulation in unstructured environments.

#### Embedded AI / HPSC Deployment & Hardware Benchmarking
Deployed robotic algorithms across heterogeneous computing architectures, including x86, NVIDIA, and NASA's RISC-V High Performance Spaceflight Computing (HPSC) platform. Cross-compiled and executed neural-network policy inference via **ONNX** on HPSC, benchmarking inference latency and throughput against NVIDIA and x86 compute platforms to characterize edge deployment trade-offs for planetary robotics.

---

### Contact-Rich & Space Manipulation

#### Mars Sample Return — In-Contact Manipulation & Wrench Estimation (MSR-SRL-STS)
Served as Cognizant Engineer (CogE) for Wrench Estimation and In-Contact Manipulation for the 7-DoF Sample Transfer Arm on NASA's Mars Sample Return [Sample Retrieval Lander](https://science.nasa.gov/mission/mars-sample-return/sample-retrieval-lander/) (SRL). 

Designed algorithms converting raw strain gauge data into gravity- and temperature-compensated force-torque wrenches, and developed core compliant contact behaviors for inserting delicate sample tubes into the Mars Ascent Vehicle (MAV) — intended to be the first continuous closed-loop robotic arm force control algorithm executed on another planet. 

<iframe width="560" height="315" src="https://www.youtube.com/embed/RnqbMj8NwfE?si=ffr0LX3juVYeecSo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### Mars Sample Return — Inter-Vehicle Robotic Docking
Following the 2024 MSR rearchitecture, served as Cognizant Engineer adapting validated Perseverance rover 5-DoF robotic arm self-docking behaviors for direct vehicle-to-vehicle sample transfer. Re-engineered kinematic frames and parameters to eliminate rover flight-software changes, culminating in a full end-to-end Engineering Model demonstration in JPL's Mars Yard:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywitbfgEGtA?si=0BFpzQkG3QryBvbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### RoMan Autonomous Mobile Manipulation (Robotics CTA)
Through the Army Research Laboratory's Robotics Collaborative Technology Alliance (RCTA), developed end-to-end autonomous manipulation capabilities on the dual-arm tracked 'RoMan' platform to perceive, grasp, and extract previously unseen, massive, and entangled debris.

![RCTA Institutions](images/rcta_centers.png)

<center> <img src="images/tool_to_teammate.png" alt="RCTA development objectives" title="RCTA development objectives" width="300"> </center>

Integrated RGB-D perception for object singulation, heuristic-free geometric grasp planning, and active wrench-reactive pose compliance, enabling the robot to safely deflect its pose and lift heavy, unmodeled loads without breakage. Published in *Field Robotics* (2022).

<center> <img src="images/roman.jpg" alt="RCTA RoMan platform" title="RCTA RoMan platform" width="600"> </center>

<iframe width="560" height="315" src="https://www.youtube.com/embed/sq1aoC5N1fs?si=URs8rpCwOWG5dZDO&amp;start=454" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

---

### Autonomous Field Robotics & High-DoF Mobility

#### Europa Lander Autonomous Surface Sampling (SAEL)
Served as Task Manager and software lead for Sampling Autonomy on the Europa Lander mission concept. Led an interdisciplinary engineering team developing an end-to-end autonomy stack integrating kinematics, visual perception, workspace analysis, force/torque proprioceptive monitoring, science site selection, and fault recovery. Successfully demonstrated fully autonomous sampling on representative lander hardware during field trials at Matanuska Glacier, Alaska. Published as lead author in [*Science Robotics* (2025)](https://www.science.org/doi/10.1126/scirobotics.adi5582).

#### Extant Exobiology Life Surveyor (EELS) Snake-like Robot
Developed the underlying motor-controller and communications infrastructure powering the [EELS](https://www.science.org/doi/10.1126/scirobotics.adh8332) robot, a highly articulated bio-inspired snake robot designed for extreme terrain, crevasses, and icy worlds. Engineered low-level EtherCAT motor control, CAN/serial device drivers, and real-time motion control profilers across dozens of actuated DoF. Featured across international media and published in [*Science Robotics* (2024)](https://www.science.org/doi/10.1126/scirobotics.adh8332).

<iframe width="560" height="315" src="https://www.youtube.com/embed/ifCIDT4X9AM?si=MBE6fOVfVa8ImYOh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

#### UPRITE & Autonomous Mode Selection
Unified PRocessing for Icy Terrain Exploration (UPRITE) investigated reinforcement learning multi-armed bandit (MAB) methods to autonomously select optimal manipulation and mobility modes under environmental uncertainty, demonstrated on JPL's Surrogate dual-arm manipulation platform:

<center> <img src="images/surrogate_artists.jpg" alt="JPL's Surrogate Robot - Artist's Impression" title="JPL's Surrogate Robot - Artist's Impression" width="500"> </center>

<center> <img src="images/surrogate.jpg" alt="JPL's Surrogate Robot - Original Configuration" title="JPL's Surrogate Robot - Original Configuration" width="500"> </center>

---

### Real-Time Systems, Embedded Hardware & Ecosystem Leadership

- **Heterogeneous Real-Time Systems**: Technical lead demonstrating robotics algorithms and deterministic Time-Sensitive Networking (TSN) across heterogeneous compute endpoints (x86, ARM, RISC-V, NVIDIA).
- **ROS 1/2 & Flight Middleware**: Developed and maintain modules running under both ROS 1 and ROS 2 from a common source base; created an automated code generator for a ROS 2–F Prime DDS bridge supporting integration between robotics research and spaceflight software.
- **Hardware Integration & Diagnostics**: Developed diagnostic tools and test procedures for EtherCAT, CAN, RS-232/422/485, motor controllers, and 6-axis force/torque sensors.
- **Industry & Ecosystem Collaboration**: Direct collaboration with external partners including Acontis (EtherCAT) and eProsima (DDS interoperability); represented JPL on industry-facing technical panels and conducted live robotics capability demonstrations at the IEEE Space Computing Conference Space Robotics Workshop to stakeholders from Microchip, BAE Systems, Disney, and others.
