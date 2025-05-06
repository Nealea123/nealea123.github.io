---
title: "Data acquisition and training of humanoid dual-arm teleoperation based on VisionPro"
date: 2025-01-07
layout: post
categories: [Imitation Learning, Teleoperation]
tags: [Imitation Learning, Operation, Manipulation, Dexterous Operation, Double Arm]
---

## Introduction
This system, based on VisionPro, focuses on data acquisition and training for humanoid dual - arm teleoperation. It uses a stereo depth camera and a 7 - DOF robotic arm with a 6 - DOF dexterous hand to capture human arm movements and translate them into robot actions. VisionPro handles multi - sensor fusion and hand tracking. The data is processed and used for imitation learning training, enabling the robot to learn and mimic human operations. The system also provides real - time visual feedback and controls the mechanical arm's movements, enhancing the efficiency and accuracy of dual - arm teleoperation

## Experiment
<html>
<body>
<div style="text-align: center">
  <iframe width="560" height="315" src="https://www.youtube.com/embed/uNdFzHEoAiw?si=chbKWSzCLK_wEnLM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
</div>
</body>
</html>

This video shows a humanoid dual - arm teleoperation experiment platform based on VisionPro. It includes a dual - arm robotic system with a 7 - DOF robotic arm and a 6 - DOF dexterous hand for performing various tasks. The setup has a stereo depth camera for capturing visual data and VisionPro for multi - sensor fusion and hand tracking. The platform allows for data acquisition from human demonstrations, which is then used for training the robot through imitation learning. It also provides real - time visual feedback and controls the mechanical arm's movements, enhancing the efficiency and accuracy of dual - arm teleoperation. This system is useful for studying and improving humanoid robot manipulation skills in a laboratory environment.

<!-- > A preprint of the paper is available at <kbd><a href="https://arxiv.org/abs/2404.12220" target="_blank" style="text-decoration: none; color: inherit;" >arXiv</a></kbd>
{: .prompt-tip } -->

<!-- , which is submitted to IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2024 -->

<!-- ## Motivation -->
<!-- ![Motivation](/images/slednav/sledinspir.bmp) -->

## Method
![Method](/images/teleop/teleop.png)

The image presents a human - like dual - arm remote operation data collection and training platform based on VisionPro. It includes a dual - arm remote operation experimental platform comprising a dual - depth - camera, a 7 - DOF robotic arm, and a 6 - DOF dexterous hand. VisionPro is used for multi - sensor fusion and tracking.

Data processing and collection involve acquiring and handling data from the sensors. The dexterous hand is reoriented to adjust its position and movement. Mechanical arm motion control manages the movement of the robotic arm. Real - time visual feedback provides immediate visual information for the operation. The collected dataset is used for imitation learning training, where the robot learns to imitate human actions and operations. Imitation learning strategy inference involves deducing the optimal strategies for the robot to perform tasks by mimicking human behavior. This system enables effective training and data collection for improving the performance of dual - arm remote operations, leveraging VisionPro's capabilities for sensor fusion and tracking to enhance the robot's ability to learn and execute complex tasks.

<!-- ![Experiment](/images/slednav/sledtest.bmp)

**Experiment result**: tractor average speed **<font color="red">≈1m/s</font>**, trailer position error **<font color="red"><10cm</font>**, and trailer yaw angle error **<font color="red"><5.25°</font>** (calculated by motion capture system) -->