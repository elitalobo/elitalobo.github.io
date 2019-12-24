---
layout: archive
title: "Projects"
permalink: /projects/
author_profile: true
---

**Soft Option-Critic** \
Hierarchical Reinforcement learning aims to solve complex tasks by learning reusable skills thatexploit the compositional structure of the task to speed up learning. The option critic architecture successfully demonstrates a way to automate the learning of these skills while solving a specific task. However, this framework uses on-policy updates which makes it highly sample inefficient and impractical for solving control tasks with high dimensional state and action space. Additionally, this framework may not necessarily generate diverse skills and often collapses to learning a single skill in naive tasks. In this work, we show how to extend options the options framework to generate diverse maximum entropy options that specialize in different parts of state-action space. Experimental results show that our proposed framework enables the agent to learn to achieve higher rewards faster than vanilla options-critic, Hierarchical RL via advantage-weighted information maximization framework(AdInfoHRL), and state of the art algorithms like PPO and Soft Actor-Critic in many control tasks in addition to learning more distinguishableIm skills. \
[Report](https://github.com/elitalobo/Hierarchical-RL-Algorithms/blob/master/soc_report.pdf) \
<img align="left" width="400" height="400" src="https://github.com/elitalobo/Hierarchical-RL-Algorithms/blob/master/maximum_entropy-option-critic/HalfCheetahBulletEnv-v0.png">
<img align="right" width="400" height="400" src="https://github.com/elitalobo/Hierarchical-RL-Algorithms/blob/master/HopperBulletEnv-v0_state-action.png">

\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
\
[Code](https://github.com/elitalobo/Hierarchical-RL-Algorithms) \
\
**Hierarchical RL Algorithms Implementation** \
Implemented Deep Option-Critic and Hierarchical RL via Advantage-Weighted Information Maximization Framework in Pytorch for solving Roboschool Tasks. \
[Code](https://github.com/elitalobo/Hierarchical-RL-Algorithms) \

**Predicting Peak Energy Demand Days of the Month** \
Goal of this project was to predict peak demand days of the
month for energy-grid (New England energy-grid dataset). \
Solution: Built a windowed multilayer perceptron model
based on history, weather conditions and other non auto-
regressive features like day of the week, is_weekend, day of
the month etc, days before any special event for hourly
demand prediction. \
Built a model to predict peak demand threshold
for a month based on weather conditions and history.
The two models combined predicts if the next day
would be the peak energy demand day of the month. 
<img align="center" width="400" height="400" src="https://github.com/elitalobo/elitalobo.github.io/blob/master/files/peak_demand_curve.png">

**Logo Infringement Detection (Flipkart Hackday 10 project):**
The goal of our hack was to provide proactive detection of fake listings and enable Flipkart to open marketplace to improve selection while still protecting customer’s as well as seller's trust in ‘Flipkart’.
We trained an in-house Mask Region-based Convolution Networks model which can detect logo infringement of 5 popular brands - Nike, Adidas, Puma, Reebok, Lotto with 88% accuracy and which can be extended to detect logo infringement of any other brand. This project won 1st place and has been exposed as a Chrome plugin to facilitate easy use by Catalogue and Marketplace team. \
\
<img align="center" width="500" height="500" src="https://github.com/elitalobo/elitalobo.github.io/blob/master/files/no_infringement.png">
<img align="center" width="400" height="400" src="https://github.com/elitalobo/elitalobo.github.io/blob/master/files/infringement_1.png"> \

**FloorPlanning using Greedy Particle Search Optimization:**  \
Developed an algorithm for efficiently minimizing floor planning area using a variant of PSO algorithm and Greedy approach. Implemented the code in C++. 
\
\
<img align="center" width="400" height="400" src="https://github.com/elitalobo/elitalobo.github.io/blob/master/files/test20.png"> \
[Code](https://github.com/elitalobo/FloorPlanningArea_Minimization_Algorithm) \

**Anomalous Payout Detector**
Developed a time-series based model based on order history and payout history that could detect anomalous payouts made to sellers due to various bugs in the continuously evolving accounting system with high accuracy.
<img align="center" width="600" height="600" src="https://github.com/elitalobo/elitalobo.github.io/blob/master/files/anomalous_payout_detection.png"> \
