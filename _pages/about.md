---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently pursung my master degree candidate in the Department of Automation, SEIEE, Shanghai Jiao Tong University. I am part of the  [CyberC3 Intelligent Vehicle Lab](https://cyberc3.sjtu.edu.cn), led by [Prof. Ming Yang](https://cyberc3.sjtu.edu.cn/people.htm). 

# 📖 Education
- *2021.09 - 2024.03*, Shanghai Jiao Tong University
  - Master of Engineering, Department of Automation; GPA: 3.56/4.00
  - Laboratory: [CyberC3 Intelligent Vehicle Lab](https://cyberc3.sjtu.edu.cn); Supervisor: Prof. Ming Yang
- *2017.09 - 2021.06*, Tongji University
  - Bachelor of Engineering, Department of Automation; GPA: 4.74/5.00, Ranking: 5/105
  - Laboratory: [Vision4robotics Lab](https://vision4robotics.github.io/); Supervisor: Prof. Changhong Fu

# 📝 Publications
- *[BAANet: Learning Bi-directional Adaptive Attention Gates for Multispectral Pedestrian Detection](https://ieeexplore.ieee.org/abstract/document/9811999),* **X. Yang**, Y. Qian, H. Zhu, C. Wang and M. Yang, **2022 International Conference on Robotics and Automation (ICRA)**, 2022
- *[Learning Consistency Pursued Correlation Filters for Real-Time UAV Tracking](https://ieeexplore.ieee.org/document/9340954)*, C. Fu, **X. Yang**, F. Li, J. Xu, C. Liu and P. Lu, **2020 IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS)**, 2020

# 🔬 Research Experience

## CyberC3 Intelligent Vehicle Lab 
<div class='paper-box'><div class='paper-box-image'><img src='images/BAANet.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">  

Advisor: Prof. Yang

Worked on *BAANet: Learning Bi-directional Adaptive Attention Gates for Multispectral Pedestrian Detection* as the first author. (Oct 2020 - Oct 2021)

- Proposed a novel multispectral pedestrian detector called BAANet. With the proposed BAA-Gate, the network could distill and recalibrate features of two modalities by stages and enhance the discriminability of fused representations.
- Introduced an adaptive interaction strategy based on illumination weighting to adaptively control the recalibration and aggregation strength between modalities and adjust their contributions to the final detection results.
- Conducted experiments and showed the competitive performance of the BAANet in terms of robustness and accuracy.

 

## Vision4Robotics Lab 

<div class='paper-box'><div class='paper-box-image'><img src='images/CPCF.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">  

Advisor: Prof. Fu

Worked on *Learning Consistency Pursued Correlation Filters for Real-Time UAV Tracking* as the second author. (Oct 2019 - Oct 2020)

- Proposed to pursue consistency of correlation filters across frames, which exploited rich temporal information in response maps and boosted the accuracy and robustness in the UAV tracking process.
- Introduced a dynamic constraint strategy to set up an adaptive restriction on the consistency level. Based on the quality of the previous response map, the dynamic constraint can adaptively adjust a suitable consistency level and further increases the flexibility to cope with object appearance changes in UAV tracking.
- Conducted experiments on challenging UAV datasets and demonstrated that the proposed tracker favorably surpasses the state-of-the-art trackers with real-time running speed (~43FPS) on a single CPU.

 

# 🚗 Internships

## Horizon Robotics
Prediction Algorithm Intern - Platform Technology Department          Apr 2023 - Present

- Researching and designing an interaction-aware prediction model for an end-to-end prediction-guided planning framework to improve the performance of planning of autonomous vehicle in highly interactive scenarios. The closed-loop simulation in Carla simulator will be carried out later to verify the effectiveness.

## QCraft (QingZhouZhiHang Technology Co. LTD)
Prediction Algorithm Intern - Planning and Control Department          Jan 2023 - Apr 2023

- Designed and implemented a prediction model for cut-in scenes to solve the problem that the deployed main model does not predict the inconspicuous cut-in vehicles in time.
- Proposed cutin-oriented features and transformer-based model for cut-in prediction task, conducted predictions in Frenet coordinate system, and improved the sensitivity and the robustness of prediction.
- Deployed the prediction model on the Nvidia Orin platform, and its inference time is 4ms, with a precision of 0.93 and a recall of 0.84, effectively assisting the main prediction model and avoiding high-risk cut-in behaviors of other vehicles in advance.

## Sensetime
Decision-making Algorithm Intern - SenseAuto / Planning and Control Department           Jan 2022- Nov 2022

- Optimization of VRU avoidance decision strategy
  - The original decision strategy of VRU avoidance is overly conservative and easily leads to emergency braking. Optimized the avoidance rules according to traffic rules and VRU interaction logic and nearly doubles the MPI.
- Rule-based and model-based abnormal parking vehicle reasoning
  - The reasoning of abnormal parking vehicles is crucial for the detour decision performance of autonomous vehicles.
  - Designed and implemented a rule-based reasoning module considering the static and dynamic environment, including agents history, maps, traffic lights, blind spots, etc. During the 700km road test, MPI for this issue increased from 70km to 150km. 
  - Designed and implemented a model-based reasoning module due to the increasing difficulty of rule maintenance. Collected abnormal parking vehicle datasets by a rule-based trigger, designed abnormal parking vehicle features and trained on the random forest algorithm, and obtained the precision of abnormal vehicle reasoning as 0.95 and the recall of 0.85.

## NIO

Perception Algorithm Intern - Autonomous Driving System / Platform Engineering Department          May 2021- Aug 2021

- Participated in the design and implementation of the evaluation system for AVP (Automated Valet Parking)  perception algorithm, including the introduction of new metrics, scenario classification and test set construction.

# 🎖 Honors and Awards

- *2021.06*         Outstanding Graduate of Tongji University
- *2017~2020*    Outstanding Student Scholarship of Tongji University
- *2019.09*         3rd prize of Shanghai Competition area, National College Students Electronic Design Competition
- *2019.08*         1st prize of the national Finals, the 14th annual NXP Cup Smart Car Competition
- *2018.05*         1st prize of the VEX Robotics Asia Championship

# 📚 Academic Services

- Reviewer for IEEE International Conference on Robotics and Automation (ICRA) 2023
- Reviewer for IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS) 2022-2023
