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
* MSc. in Robotics, King’s College London, 2023
* B.S. in Electrical Engineering and Automation, Harbin Institute of Technology, 2019


Research experience
======
* Jun. 2025 - now: Research Assistant
  * Eastern Institute of Technology
  * Duties includes: Collecting baseline demonstration data on Franka,
  * Supervisor: Dr Xiaocong Li

* Jun. 2025: Team Leader 
  * LeRobot Worldwide Hackathon Online
  * Duties included:
    1)Collecting desktop cleanup task data with robot SO-101, generating policy network parameters based on the data and ACT policy, deploying trained policy in SO-101, recording the results of SO-101in real-world task.
    2)Collecting data in MuJoCo, adapting HIL-SERL policy to handle variations in different tasks，improving the visual backbone to speed up training and improve generalization, Simulating robot SO-101 Tasks, and fine tuning reward.
  * Team Member: Xinyu Song

* Oct. 2024 - Mar. 2025: Research Assistant
  * National University of Singapore
  * Duties included:
    1) Collecting data in Maniskill2, designing reward, training PPO policy for Dual-arm robotics to grasp irregularly-shaped containers, adding constraints + affordance collection.
    2) Making simulations in Drake and fine tuning, then transferring to real based on affordance prediction and RL policy.
  * Supervisor: Dr. Harold Soh, Mr. Ce Hao
  
* Dec. 2023 - Aug. 2024: Research Assistant
  * Shandong Sport University
  * Duties includes:
    1）Collecting data with Franka robot, using Regression model and PCA to analysis correlation between joint points
    2）Using deep neural network based on HMM to predict motion trajectory, correcting athletes’ actions with trained model.
  * Supervisor: Prof. Dianbo Zhang

* Dec. 2022 - Aug. 2023: Master Thesis
  * King’s College London 
  * Duties included:
    1）Collecting data in MATLAB with the simulation model provided by TU Dresden, analysing the hydrogel motion pattern and calculating the fitting function.
    2）Designing model-based RL controller and classic feedback controller to control hydrogel and evaluating the factors affecting the controlling performance.
  * Supervisor: Dr.Matthew Howard

* Jan. 2021 - Aug. 2022: Research Assistant
  * King’s College London 
  * Duties included:
    1）Using OpenPose and CNN to estimate the pose of people and identified their social activity status.
    2) Building a GNN network and used link prediction to classify groups with the same social activities.
  * Supervisor: Dr.Oya Celiktutan

* Aug. 2019 - Aug. 2020: Research and Innovation Fund Project of Harbin Institute of Technology, student leader
  * Harbin Institute of Technology 
  * Duties includes:
    1) Used data mining algorithms such as SVM to build an effective classification model for wind power ramp events.
    2) Built a multi-layer BP neural network to predict intermittent of wind farm and provided power generation strategies.

* Sep. 2018 - Aug. 2019: Bachelor thesis
  * GHarbin Institute of Technology
  * Duties included:
    1) Clarifying the concepts and interrelationships among wind power uncertainty, randomness, volatility, and intermittency, proposing a characterization indicator for wind power intermittency based on wind speed intermittency metrics, analyzing the diurnal and annual periodicity of wind power intermittency.
    2) Designing a neural network algorithm to predict the intermittency of a single wind turbine, constructing a virtual wind farm using correlation analysis, predicting wind farm-level intermittency using a neural network model.
  * Supervisor: Prof.Yufeng Gu


Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Patents
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Honours and Award
======
* Excellent Graduation Thesis.  Jun.2019
* The third prize of Harbin Institute of Technology at the National College Students Social Practice and Science & Tech Competition on Energy Conservation and Emission Reduction. May. 2019

  

