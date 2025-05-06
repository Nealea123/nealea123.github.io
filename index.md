---
layout: page
---
# Yaohang Xu (许耀航)
I am a highly-motivated person interested in robotics. My research goal is to establish a robot system with high generalization, robustness, intelligence and the ability to independently complete complex and dexterous long-series operation tasks. So my research is the intersection of robots, dexterous operation, large models and reinforcement learning. Since 2023, I have been pursuing a M.Sc. in School of Artificial Intelligence and Automation at Huazhong University of Science and Technology (HUST) under the supervision of Prof. Lijun Zhu. I received my B.Eng. in School of Artificial Intelligence and Automation at Huazhong University of Science and Technology (HUST) in 2023.

<!-- <center class="half">
    <img src="/images/rm/robots.jpg" width="400"/>
    <img src="/images/rm/operate.jpg" width="400"/>
</center> -->

<!-- <div style="border: 0px solid #1182BF;padding: 4px;">
    <p style="text-align: justify;"> <img class="right" src="/images/rm/robots.jpg" width="490px" /> I am a highly-motivated person interested in robotics. My research goal is to build agile, safety, intelligent, and autonomous mobile robot systems. So my research lies in the intersection of robotics, planning, optimization, and control. Since 2022, I have been concurrently pursuing a M.Sc. in School Artificial Intelligence and Automation at Huazhong University of Science and Technology (HUST) under the supervision of Prof. Lijun Zhu. I received my B.Sc. in School of Control Engineering at Northeastern University at Qinhuangdao (NEUQ) in 2022.</p>
</div> -->
<!-- <div style="text-align: center">
    <p style="font-weight: bold">I am seeking a PhD position starting in Fall 2025.</p>
</div> -->
<!-- <p style="margin-top: 10px;">chigui-2 motion video in May, 2022</p> -->
<!-- Where I spent wonderful time with my friends, teammates, and teachers. -->

<img class="center" src="/images/person/robocon.jpg" width="600px"  alt="robots" />
<!-- ![robots](/images/rm/robots.jpg) -->

<!-- ## Education
---
**HuaZhong University of Science And Technology**, China 09/2022 - Present  
*Master* student in Control Science and Engineering, expected June 2025 (GPA 91.96/100)  
**Northeastern University at Qinhuangdao**, China 09/2018 - 06/2022  
*Bachelor* in Technique and Instrumentation of Measurements (GPA 92.22/100)   -->


<!-- <div style="border: 0px solid #1182BF; padding: 4px;">
    <h3><b>News</b></h3>
    <ul>
        <li><em>Jun. 2024</em>: Two paper (1st, 2nd author) have been accepted by IROS 2024.</li>
        <li><em>May. 2024</em>: Participated in ICRA 2024 (Yokohama, Japan). Honorary to present an Oral Presentation!</li>
    </ul>
    <details>
        <summary><b>Old News</b></summary>
        <ul>
            <li><i>May. 2024</i>: Participated in ICRA 2024 (Yokohama, Japan). Honorary to present an Oral Presentation!</li>
            <li><i>May. 2024</i>: Participated in ICRA 2024 (Yokohama, Japan). Honorary to present an Oral Presentation!</li>
        </ul>
    </details>
</div> -->

## Awards & Honors
---
• National College Robot Competition ROBOCON(2024, Second Place of National First Prize)  
• National College Robot Competition ROBOCON(2023, National First Prize)  
• Huazhong University of Science and Technology Outstanding Graduate(2023, University Level)  
• Mathematical Contest In Modeling(2022, Honorable Mention)  
• Outstanding student leader of the school(2020, University Level)  

## Skills
---
• Software: GAZEBO, MUJOCO, Isaac Sim, MATLAB, Altium Designer, Keil, SolidWorks  
• Programming: Pytorch, JAX, C/C++, Python for Linux(ROS)  
• Engineering: Circuit/PCB Design and Debug, Mechanical Assembly  
• Soft Skills: Planned, Responsible, Organized, Self-Motivating, Teamwork, Adaptability, Analytical Thinking  



## Project
---

### [Long-order operation tasks for skill reinforcement learning of residual hypernetworks](posts/PiperHil)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/hil/hil_hyper.png" width="500px" alt="sledrobotoutdoor" />A reinforcement learning system based on residual hypernetwork pools and real-time human demonstrations is proposed to achieve robust learning for long-order and complex arm operation tasks. This system enables the robotic arm to continuously try and explore through reinforcement learning. It first trains the basic model for grasping, and then learns different branch skills through the hypernetwork pool. Under the real-time teaching of the operator, it acquires more refined operation skills and features high robustness and a 100% success rate.</p>
</div>


### [Data acquisition and training of humanoid dual-arm teleoperation based on VisionPro](posts/ActDeploy)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/teleop/teleop.png" width="500px" alt="sledrobotoutdoor" /> The image presents a human - like dual - arm remote operation data collection and training platform based on VisionPro. It includes a dual - arm remote operation experimental platform comprising a dual - depth - camera, a 7 - DOF robotic arm, and a 6 - DOF dexterous hand. VisionPro is used for multi - sensor fusion and tracking.
    Data processing and collection involve acquiring and handling data from the sensors. The dexterous hand is reoriented to adjust its position and movement. Mechanical arm motion control manages the movement of the robotic arm. Real - time visual feedback provides immediate visual information for the operation. The collected dataset is used for imitation learning training, where the robot learns to imitate human actions and operations. Imitation learning strategy inference involves deducing the optimal strategies for the robot to perform tasks by mimicking human behavior. This system enables effective training and data collection for improving the performance of dual - arm remote operations, leveraging VisionPro's capabilities for sensor fusion and tracking to enhance the robot's ability to learn and execute complex tasks.</p>
</div>


### [ACT Imitation Learning of Operate Box with ROS/Gazebo simulation](posts/GazeboSim)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/imitation/imitation_learning.png" width="500px" alt="sledrobotoutdoor" /> This experiment uses imitation learning in a ROS/Gazebo simulation to train a robot for box - operating tasks. The robot learns to grasp, move, and place colored cubes by mimicking human actions. The learning outcome is demonstrated in the simulation environment, with a window in the top - left showing the robot's - perspective image, aiding environmental perception and decision - making. This approach allows the robot to acquire efficient manipulation skills through observation and imitation, leveraging the high - fidelity simulation capabilities of ROS/Gazebo to facilitate the development of complex robotic behaviors in a controlled and safe setting.</p>
</div>

## Research
---

### [Prescribed-Time Robust Synchronization of Networked Heterogeneous Euler-Lagrange Systems](posts/ArmPaper)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/arm/arm.png" width="500px" alt="sledrobotoutdoor" /> In this paper, we propose a prescribed-time synchronization (PTS) algorithm for networked Euler-Lagrange systems subjected to external disturbances. Notably, the system matrix and the state of the leader agent are not accessible to all agents. The algorithm consists of distributed prescribed-time observers and local prescribed-time tracking controllers, dividing the PTS problem into prescribed-time convergence of distributed estimation errors and local tracking errors. Unlike most existing prescribed-time control methods, which achieve prescribed-time convergence by introducing specific time-varying gains and adjusting feedback values, we establish a class of KT functions and incorporate them into comparison functions to represent time-varying gains. By analyzing the properties of class KT and comparison functions, we ensure the prescribed-time convergence of distributed estimation errors and local tracking errors, as well as the uniform boundedness of internal signals in the closed-loop systems. External disturbances are handled and dominated by the time-varying gains that tend to infinity as time approaches the prescribed time, while the control signal is still guaranteed to be bounded. Finally, a numerical example and a practical experiment demonstrate the effectiveness and innovation of the algorithm.</p>
</div>






<!-- ### [Hybrid Dynamics Modeling and Trajectory Planning for a Cable-Trailer System with a Quadruped Robot](posts/SledNav)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/slednav/sledrobotoutdoor.jpg" width="500px" alt="sledrobotoutdoor" /> Inspired by the utilization of dogs in sled-pulling for transportation, we introduce a cable-trailer system with a quadruped robot. The motion planning of the proposed robot system presents challenges arising from the nonholonomic constraints of the trailer, system underactuation, and hybrid interaction through the cable. To tackle these challenges, we develop a hybrid dynamics model that accounts for the cable's taut/slack status. Since it is computationally intense to directly optimize the trajectory, we first propose a search algorithm to compute a sub-optimal trajectory as the initial solution. Then, a novel collision avoidance constraint based on the geometric shapes of objects is proposed to formulate the trajectory optimization problem for the hybrid system. The proposed trajectory planning method is implemented on a Unitree A1 quadruped robot with a customized cable-trailer and validated through experiments.</p>
</div>


### [Agile and Safe Trajectory Planning for Quadruped Navigation with Motion Anisotropy Awareness](posts/AgileNav)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/agilenav/systemoverview.bmp" width="500px" alt="systemoverview"/> Quadruped robots demonstrate robust and agile movements in various terrains; however, their navigation autonomy is still insufficient. One of the challenges is that the motion capabilities of the quadruped robot are anisotropic along different directions, which significantly affects the safety of quadruped robot navigation. This paper proposes a navigation framework that takes into account the motion anisotropy of quadruped robots including kinodynamic trajectory generation, nonlinear trajectory optimization, and nonlinear model predictive control. In simulation and real robot tests, we demonstrate that our motion-anisotropy-aware navigation framework could: (1) generate more efficient trajectories and realize more agile quadruped navigation; (2) significantly improve the navigation safety in challenging scenarios. The implementation is realized as an open-source package at <a href="https://github.com/ZWT006/agile_navigation" target="_blank" >agile_navigation: Quadruped Robot Planning ROS Package (github.com)</a></p>
</div>

### [Quadruped Robot Planning Framework for Navigation, Formation, Collaboration, and Flocking](posts/MultiAgent)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/multinav/framework.bmp" width="500px" alt="framework" /> After multiple optimization iterations, we developed and deployed the complete navigation framework, encompassing both hardware and software. The hardware is characterized by its compactness and lightweight design. Meanwhile, the software integrates perception, planning, and control functionalities, facilitating the seamless deployment of various algorithms. Several of our projects leverage this framework, spanning quadruped robot navigation, formation control, collaboration, and flocking.</p>
</div>

### [chigui: A novel Spherical Robot Drive by Barycenter Offset and Conservation of Angular Momentum](posts/Robotchigui)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/ballbot/chigui.bmp" width="200px" alt="chigui" /> The spherical robot chigui integrates the drive principles of Barycenter Offset (BCO) and Conservation of Angular Momentum (COAM), propelled by three motors with two reaction wheels. Employing the Euler-Lagrange system dynamics model based on the d’Alembert principle, we analyze the robot's motion behavior and introduce three basic robot motions to simplify the dynamics model and derive equations for external torque input motion. We design a cascade controller for the robot's basic motion and establish a ROS-Gazebo physical simulation platform for algorithm testing. Additionally, we assemble mechanical structures, develop a hardware control system, and author embedded real-time control code for experimentation.</p>
</div>

### [Wheeled Robot for RoboMaster University Series Competition](posts/RobotWheeled)
<div style="border: 0px solid #1182BF;padding: 4px;">
    <p> <img class="left" src="/images/rm/hero2.jpg" width="200px" alt="hero"/> The RoboMaster University Series (RMU) is a platform for robotic competitions and academic exchange, specially designed for global technology enthusiasts. It requires participants to go beyond their textbooks to form robotics teams, develop a diverse fleet of robots, and participate in team battles. I participated RMU2021 with my teammates as leader of the Electric Control Group. We design schemes, make circuit boards, and debug embedded programs. We tirelessly tested and optimized our robots, and endured countless sleepless nights. It' a memorable and cherished time.</p>
</div> -->


---
<div style="text-align: center">
    <a href="https://m.maploco.com/details/bd968osl"><img style="border:0px;" src="https://www.maploco.com/vmap/s/10483077.png" alt="Locations of Site Visitors" title="Locations of Site Visitors"/></a>   
</div>