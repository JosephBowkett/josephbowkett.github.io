---
permalink: /
title: "Bio"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I'm a Group Lead for Robotic Manipulation and Sampling within the Robotic Mobility & Manipulation section of NASA's Jet Propulsion Laboratory. My interests focus around what is termed behavior level or 'functional' autonomy for robotic tasks, particularly in regard to grasping and manipulation, employing both proprioception and exteroception to build understanding of unstructured task spaces.

Some of the projects I've been working on recently include:

Mars Sample Return, Sample Retrieval Lander, Sample Transfer System (MSR-SRL-STS)
------

I acted as the Cognizant Engineer (CogE) for one or more robotic capabilities through two design iterations of NASA's Mars Sample Return (MSR) program. In the circa. 2023 MSR architecture, with a fully featured [Sample Retrieval Lander](https://science.nasa.gov/mission/mars-sample-return/sample-retrieval-lander/) (SRL), I took on the role of CogE for Wrench Estimation plus In-Contact Manipulation of the Sample Transfer Arm. This large 7-DoF robotic arm would retrieve rock sample tubes either from the Perseverence Rover, or off the ground when deposited by Sample Retrieval Helicopters. My role was to design the code that turned raw strain gauge measurements at the wrist sensor into gravity and temperature compensated force-torque tuples. I then took those measurements and worked out how to manipulate the delicate sample tubes, such as inserting them into the Mars Ascent Vehicle; which would have required the first use of a continuous, closed loop robotic arm force control algorithm on another planet. An end-to-end demonstration of the fully autonomous sample extraction, insertion, and MAV lid placement was released here:

<iframe width="560" height="315" src="https://www.youtube.com/embed/RnqbMj8NwfE?si=ffr0LX3juVYeecSo" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

After the 2024 rearchitecture, I shifted roles to be Cognizant Engineer for Inter-vehicle docking, or using the existing 5-DoF robotic arm on the Perseverence Rover to deliver sample tubes directly into a smaller SRL, while attempting to eliminate any need for changes to software on the rover itself. It involved studying all the existing capabilities of the robotic arm, along with all the validated sets of parameters that accompanied existing self-docking behavior (for exchanging drill bits), then transforming various matrices to permit docking with another vehicle. This culiminated in an end-to-end inter-vehicle docking demonstration in JPL's Mars Yard, using the Engineering Model of the Perseverence rover:

<iframe width="560" height="315" src="https://www.youtube.com/embed/ywitbfgEGtA?si=0BFpzQkG3QryBvbr" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>


Extant Exobiology Life Surveyor (EELS)
------

I had the privilege to develop the motor controller infrastructure that underpins the motion control capabilities of the Extant Exobiology Life Surveyor research [EELS](https://www.science.org/doi/10.1126/scirobotics.adh8332) project, as has been featured across several [media outlets](https://www.latimes.com/science/story/2023-08-24/jpl-search-life-watery-worlds-slithering-robot).

<iframe width="560" height="315" src="https://www.youtube.com/embed/ifCIDT4X9AM?si=MBE6fOVfVa8ImYOh" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

Sampling Autonomy for an Europa Lander (SAEL)
------

I end up as task manager for the SAEL task at JPL, investigating problems relating to sampling peculiar to icy moons such as Europa, where biosignatures of life in liquid oceans deep inside the ice crust might be found just under the surface, out of reach of the high radiation from the Jovian magnetosphere. This culminated in a [field trial](https://www.science.org/doi/10.1126/scirobotics.adi5582) at Matanuska Glacier, AK, where a cross-disciplinary team demonstrated autonomous end-to-end sampling activities with representative lander hardware.

Robotics Collaborative Technology Alliance
------

![RCTA Institutions](images/rcta_centers.png)

Funded by the Army Research Laboratory, the Robotics Collaborative Technology Alliance (RCTA) brought together a number of research institutions to further aspects of robotics research that could facilitate the fielding of autonomous systems within active deployment zones to act as team members rather than just tools.

<center> <img src="images/tool_to_teammate.png" alt="RCTA development objectives" title="RCTA development objectives" width="300"> </center>

My area of focus has been on manipulation of previously unseen large and unweildly objects within piles, such as might be encountered within an urban deployment setting. The platform developed to demonstrate this and other manipulation capabilities is named 'RoMan', a tracked dual arm robot developed using technology licensed from the Jet Propulsion Laboratory.

<center> <img src="images/roman.jpg" alt="RCTA RoMan platform" title="RCTA RoMan platform" width="600"> </center>

We're using Roman to perceive, grasp, and transport a diverse range of large items, some with a model but most without. This employs RGBD vision to singulate objects and reason about their connectedness, grasp planning once a candidate object is found, and wrench reactive control, to allow the end effector to deflect its pose while lifting the heavy objects.

<iframe width="560" height="315" src="https://www.youtube.com/embed/sq1aoC5N1fs?si=URs8rpCwOWG5dZDO&amp;start=454" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

UPRITE
------
Unified PRocessing for Icy Terrain Exploration (UPRITE) is a strategic Research & Technology Development project at the Jet Propulsion Laboratory aimed at developing a means of autonomously selecting between discrete operating modes for a given task. It does this through an extension of a reinforcement learning algorithm named Multi-Armed Bandit theory, which attempts to intelligently select between different actions to maximize some payoff, without a priori knowledge of the reward given by each task.

The manipulation side of the project is utilizing JPL's Surrogate platform:

<center> <img src="images/surrogate_artists.jpg" alt="JPL's Surrogate Robot - Artist's Impression" title="JPL's Surrogate Robot - Artist's Impression" width="500"> </center>

<center> <img src="images/surrogate.jpg" alt="JPL's Surrogate Robot - Original Configuration" title="JPL's Surrogate Robot - Original Configuration" width="500"> </center>

