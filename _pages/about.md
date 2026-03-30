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

Through two design iterations of NASA's Mars Sample Return, Sample Retrieval Lander (MSR-SRL) I was initially the Cognicant Engineer for Active Compliance and Wrench Estimation, then for Inter-vehicle Docking. In the first of these, a large 7-DoF robotic arm attached to [SRL itself](https://science.nasa.gov/mission/mars-sample-return/sample-retrieval-lander/) would retrieve rock sample tubes either from the Perseverence Rover, or off the ground when deposited by Sample Retrieval Helicopters. My role invovled design the force-torque sensing at the wrist of the robotic arm, as well as how those measurements were built into a dexterous force control algorithm.

After the 2024 rearchitecture, I shifted roles to being Cognizant Engineer for Inter-vehicle docking, or using the existing 5-DoF robotic arm on the Perseverence Rover to deliver sample tubes directly into a smaller SRL, while attempting to eliminate any need for changes to software on the rover itself.

Extant Exobiology Life Surveyor (EELS)
------

I had the privilege to develop the motor controller infrastructure that underpins the motion control capabilities of the Extant Exobiology Life Surveyor research [EELS](https://www.science.org/doi/10.1126/scirobotics.adh8332) project, as has been featured across several [media outlets](https://www.latimes.com/science/story/2023-08-24/jpl-search-life-watery-worlds-slithering-robot).

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

