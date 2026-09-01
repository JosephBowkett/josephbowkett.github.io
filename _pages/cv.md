---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
  - /cv.html
---

{% include base_path %}

<div class="notice--info" style="margin-bottom: 2em;">
  <strong>Download Resume PDFs:</strong><br>
  • <a href="/files/Bowkett_Resume_IC.pdf" target="_blank"><strong>Robotics Systems / IC Resume (PDF)</strong></a><br>
  • <a href="/files/Bowkett_Resume_Manager.pdf" target="_blank"><strong>Robotics Engineering Leadership / Manager Resume (PDF)</strong></a>
</div>

## Professional Summary
Senior robotics systems engineer and engineering leader with 13 years of experience developing, integrating, and deploying autonomy, control, manipulation, locomotion, and embedded compute capabilities on physical robotic platforms across NASA JPL, Caltech, and commercial engineering. Group Lead for Robotic Manipulation & Sampling at JPL, combining formal people mentorship and technical leadership with hands-on contributions across robot control, real-time systems, hardware interfaces, and multi-DoF platform integration.

---

## Technical & Leadership Expertise

- **Robotics & Control**: Contact-rich manipulation, continuous force/compliance control, locomotion, analytical kinematics & IK, collision detection, grasp planning, motion planning, perception-guided manipulation, functional autonomy, teleoperation, robot diagnostics.
- **Robot Learning & Inference**: Reinforcement learning mentorship (PPO in NVIDIA Isaac Lab), Vision-Language-Action (VLA) research mentorship, ONNX model export & target-platform inference, embedded neural-network deployment & compute benchmarking.
- **Software & Frameworks**: Modern C++, Python, C99, Bash, CMake, ROS 1 & ROS 2, F Prime, DDS, CASAH, UR, KUKA.
- **Embedded & Robot Hardware**: EtherCAT driver development, CAN, RS-232/422/485, 6-axis force/torque sensors, 4–20 mA, 0–10 V, analog/digital I/O, embedded electronics, motor-control infrastructure.
- **Compute & Infrastructure**: RISC-V / HPSC, NVIDIA compute platforms, x86, ARM / STM32, Linux kernel & systems administration, cross-compilation, Docker, GitLab/GitHub CI, Time-Sensitive Networking (TSN).
- **Engineering Leadership**: Group leadership & people management, career mentorship, task/program management, cross-functional execution, external partner/vendor collaboration (Acontis, eProsima), research-to-hardware delivery.

---

## Work Experience

### NASA Jet Propulsion Laboratory — Pasadena, CA, USA
**Robotics Technologist & Group Lead – Robotic Manipulation & Sampling** | *March 2020 – Present*

* **Group Leadership & Mentoring**: Serve as Group Lead for Robotic Manipulation & Sampling, providing formal career mentorship, technical guidance, and resource allocation across manipulation, controls, autonomy, embedded systems, and robot integration.
* **Embedded AI / HPSC Deployment**: Deployed robotic algorithms across heterogeneous spaceflight-compute architectures (x86, NVIDIA, RISC-V High Performance Spaceflight Computing). Cross-compiled and executed neural policy inference via ONNX on HPSC, benchmarking inference latency and throughput against NVIDIA and x86 CPU platforms.
* **Learning-Based Locomotion & VLA Research**: Technical mentor for developing PPO locomotion policies in NVIDIA Isaac Lab for an 18-DoF wheel-on-limb robot across irregular terrain, guiding policy architecture, ONNX export, and target-platform inference. Mentor a separate research effort investigating VLA foundation models for dexterous manipulation.
* **Mars Sample Return — Force-Controlled Manipulation**: Cognizant Engineer for Wrench Estimation & In-Contact Manipulation on the 7-DoF Sample Transfer Arm. Led development of wrench estimation, gravity/temperature compensation, compliant contact behaviors, and sample-tube insertion into the Mars Ascent Vehicle (MAV).
* **Mars Sample Return — Inter-Vehicle Docking**: Following the 2024 rearchitecture, served as Cognizant Engineer adapting validated Perseverance rover 5-DoF arm self-docking for direct vehicle-to-vehicle transfer, culminating in an end-to-end Engineering Model demonstration in JPL's Mars Yard.
* **Europa Lander Autonomous Manipulation**: Task Manager and software lead for Sampling Autonomy, integrating kinematics, control, perception, proprioception, science targeting, and fault recovery into an end-to-end sampling system demonstrated at Matanuska Glacier, Alaska (*Science Robotics* 2025).
* **Robotic Control-Stack & Real-Time Development**: Developed motor-controller infrastructure for the bio-inspired EELS snake robot (*Science Robotics* 2024); developed/maintain reusable robot-control infrastructure spanning EtherCAT, force/torque sensing, CAN/serial, ROS 1/2, and Linux compute.
* **Heterogeneous Real-Time Systems & Middleware**: Lead technical development demonstrating robotics algorithms and deterministic Time-Sensitive Networking (TSN) across heterogeneous endpoints; built an autogenerator for a ROS 2–F Prime DDS bridge.
* **External Partner & Ecosystem Interface**: Direct technical collaboration with Acontis (EtherCAT) and eProsima (DDS); panelist and live demonstrator at IEEE Space Computing Conference Space Robotics Workshop (Microchip, BAE Systems, Disney).

### NASA Jet Propulsion Laboratory — Pasadena, CA, USA
**Research Affiliate** | *April 2016 – February 2020*

* **RoMan Autonomous Manipulation**: Developed an end-to-end system combining RGB-D perception, object selection, grasp planning, proprioceptive control, and force/wrench-reactive extraction of previously unseen massive debris on a mobile manipulator (*Field Robotics* 2022).
* **Autonomy & Controls Research**: Investigated reinforcement-learning multi-armed bandit (MAB) methods for autonomous manipulation-mode selection, deep-learning manipulation outcome assessment, and MPC/input-shaping for flexible manipulators.

### PowerbyProxi Ltd — Auckland, New Zealand
**Embedded Electronics Engineer / Engineering Intern** | *November 2011 – July 2014*

* Developed embedded C software and electrical/mechanical hardware for commercial inductive wireless power products, including PIC32 microcontrollers, custom PCBs, CAN, RS-232, Ethernet, and automated test equipment.
* Led an engineering-intern team developing a novel RF pairing technique and worked directly with commercial customers including John Deere to define requirements and establish delivery schedules.

---

## Education

### California Institute of Technology (Caltech) — Pasadena, CA, USA
**Doctor of Philosophy (Ph.D.) in Mechanical Engineering** | *2020*  
**Master of Science (M.S.) in Mechanical Engineering** | *2016*  
* *Honors*: Sir William Pickering Fellowship (Burdick Robotics Lab)  
* *Doctoral Research*: Functional autonomy for manipulation in uncertain environments, including reinforcement-learning-based mode selection, neural-network outcome assessment, visual grasp reasoning, force-aware manipulation, and robot control.

### University of Auckland — Auckland, New Zealand
**Bachelor of Engineering (Honours) in Mechatronics Engineering** | *2013*  
* *GPA*: 8.0/9.0 (First Class Honours, ~4.0/4.0 Caltech equivalent)

---

## Selected Publications

* **Bowkett J. et al.**, *"Autonomous Surface Sampling for the Europa Lander Mission Concept,"* **Science Robotics**, 2025. [DOI: 10.1126/scirobotics.adi5582](https://doi.org/10.1126/scirobotics.adi5582)
* **Dolci T., Bowkett J. et al.**, *"Robotics Capabilities Development for Mars Sample Return Transfer Activities,"* **IEEE Aerospace Conference**, 2025.
* **Bowkett J. et al.**, *"Challenges in Closed-loop Compliant Motion Control for Planetary Robotics,"* **IEEE Aerospace Conference**, 2024.
* **Vaquero T. et al., including Bowkett J.**, *"EELS: Autonomous Snake-like Robot with Task and Motion Planning Capabilities for Ice World Exploration,"* **Science Robotics**, 2024. [DOI: 10.1126/scirobotics.adh8332](https://doi.org/10.1126/scirobotics.adh8332)
* **Bowkett J., Karumanchi S., Detry R.**, *"Grasping and Transport of Unstructured Collections of Massive Objects,"* **Field Robotics**, 2022. [DOI: 10.1002/rob.22080](https://doi.org/10.1002/rob.22080)
* **Massari L. et al., including Bowkett J.**, *"Tactile Sensing and Control of Robotic Manipulator Integrating Fiber Bragg Grating Strain-Sensor,"* **Frontiers in Neurorobotics**, 2019.
* **Reid W. et al., including Bowkett J.**, *"Actively Articulated Wheel-on-Limb Mobility for Traversing Europa Analogue Terrain,"* **Field and Service Robotics**, 2019.

*Complete publication list and metrics available on [Google Scholar](https://scholar.google.com/citations?user=Gacl34sAAAAJ).*
