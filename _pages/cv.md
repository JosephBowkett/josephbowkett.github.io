---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Mechatronics (1st class honours), 2013
* M.S. in Mechanical Engineering, California Institute of Technology, 2016
* Ph.D in Mechanical Engineering, California Institute of Technology, 2020

Work experience
======
NASA Jet Propulsion Laboratory 2020-Present: Robotics Technologist & Group Lead
* Mars Sample Return - Sample Retrieval Lander (SRL) - Sample Transfer System:
  * Robotics Cognizant Engineer: M2020-SRL Docking (2024-present)
    * Managing the transfer of existing Perseverence Rover self docking algorithm to docking with SRL
  * Robotics Cognizant Engineer: Wrench Estimation (2022-2024)
    * Owning tne processing of raw aignals from the Sample Transfer Arm Force Torque Sensor
    * Defining wrench transformations, filtering, and tare behaviors
  * Robotics Cognizant Engineer: In-Contact Manipulation (2022-2024)
    * Defining all control algorithms relating to forceful interactions between the Sample Transfer Arm and various stations to transport sample tubes
* Sampling Autonomy Europa Lander: Task Manager (2021-2024)
  * Architecting software infrastructure for fully autonomous surface sampling operations for a prospective science mission to thr icy moon Europa
  * Managing team of 6 developers implementing autonomy infrastructure and sampling behaviors
* Extant Exobiology Life Surveyor (EELS): Motor control interface dev (2020-2022)
  * Configuring and modifying low level motor controller interfaces using EtherCAT and trapezoidal profilers
  
Skills
======
* Python, C++, C, MATLAB, Simulink, JMP
* Docker, GitLab/GitHub CI, Python VirtualEnv
* Signal Filtering, Controls Modeling & Design, Robotic Kinematics, RL, CNNs, hierarchical state machines

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
