---
title: "ACT Imitation Learning of Operate Box with ROS/Gazebo Simulation"
date: 2024-07-06
layout: post
categories: [reproduce, imitation learning]
tags: [imitation learning, operation, manipulation]
---

## Introduction
This experiment is carried out in the Gazebo simulation platform and focuses on the dual - arm robot operation handover and block - placement tasks based on action - block imitation learning. The main steps are as follows:

**Data Collection:** First, a series of motion data are collected by having a human operator manually control a dual - arm robot to perform operation handover and block - placement tasks in the simulation environment. These data include joint angles and trajectory information.
Model Training: An imitation learning model is trained using the collected data. The model can learn the action patterns of human operators, thereby learning to accurately perform dual - arm handovers and place blocks in designated positions.

**Simulation Experiment:** The trained model is applied to the Gazebo simulation environment. In the simulation experiment, the dual - arm robot executes operation handover and block - placement tasks based on the learned strategy. The success rate and accuracy of the robot in completing the tasks are observed and evaluated through multiple experiments, and various data during the experiment are recorded for further analysis and model optimization.

**Optimization and Improvement:** The model is adjusted and optimized according to the experimental results to improve the performance of the robot in actual operations, enabling it to complete tasks more stably and efficiently.
This experiment aims to explore the effective control of dual - arm robots in complex operation tasks using imitation learning methods, providing a theoretical foundation and technical support for the future application of dual - arm robots in industrial scenarios.

## Experiment
<html>
<body>
<div style="text-align: center">
    <iframe width="560" height="315" src="https://www.youtube.com/embed/-zkP5HXGnP4?si=oCwRMgIF-jOYYoM9" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>
  <p style="margin-top: 10px;">chigui-2 motion video in May, 2022</p>
</div>
</body>
</html>

The video shows a robot imitation learning experiment based on ROS/Gazebo. In the simulation environment, a robotic arm is operating a red and blue cube on the workbench. The "color_image" window in the top left corner displays the image information from the perspective of the robotic arm. This experiment aims to train the robot to complete cube manipulation tasks through imitation learning.

<!-- > A preprint of the paper is available at <kbd><a href="https://arxiv.org/abs/2404.12220" target="_blank" style="text-decoration: none; color: inherit;" >arXiv</a></kbd>
{: .prompt-tip } -->

<!-- , which is submitted to IEEE/RSJ International Conference on Intelligent Robots and Systems (IROS), 2024 -->

<!-- ## Motivation -->
<!-- ![Motivation](/images/slednav/sledinspir.bmp) -->

## Method
![Training](/images/imitation/ACT_training.png)

The figure presents a training process based on action block imitation learning.  In Step 1, it samples data from a demo dataset, including RGB images and joints information, to form an action sequence.  Step 2 involves inferring z through a transformer encoder with self - attention blocks, embedding joints and action sequences.  In Step 3, it uses a ResNet18 and transformer encoder and decoder to predict the action sequence, incorporating position embeddings and linear layers to output the predicted actions.

![Test](/images/imitation/ACT_test.png)

The figure illustrates a Transformer - based testing process for predicting action sequences. ResNet18 extracts features from images of four cameras. These features, combined with sinusoidal position embeddings, are fed into a Transformer encoder. The encoder processes them and passes to a Transformer decoder, which generates the predicted action sequence with the aid of position embeddings.

<!-- ![Experiment](/images/slednav/sledtest.bmp)

**Experiment result**: tractor average speed **<font color="red">≈1m/s</font>**, trailer position error **<font color="red"><10cm</font>**, and trailer yaw angle error **<font color="red"><5.25°</font>** (calculated by motion capture system) -->