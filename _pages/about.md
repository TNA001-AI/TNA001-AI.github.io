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

I'm a first-year M.S. student from [Department of Mechanical Engineering](https://www.me.columbia.edu/), [Columbia University](https://www.columbia.edu/). My research interest includes robotics, robot manipulator, artificial intelligence, control and cloud-based vehicle control.

You can find my CV here: [Tao's Curriculum Vitae](../assets/Naian_Tao_CV.pdf).

[Email: tao.naian@columbia.edu](mailto:tao.naian@columbia.edu)

[LinkedIn: linkedin.com/in/naian-tao](linkedin.com/in/naian-tao)


# 📖 Educations
Mechatronics Modeling & Simulation
- *Aug 2024 – Present*. [Columbia University](https://www.columbia.edu/), New York, NY, US
  - M.S. in Mechanical Engineering (Robotics Track)
  - Courses: Robotics Studio, Reinforcement Learning, Control

- *Aug 2023 - Jun 2024*. [University of Detroit Mercy](https://www.udmercy.edu/), Detroit, MI, US
  - B.E. in Mechatronics, Robotics, and Automation Engineering, GPA: 3.81/4.00
  - Courses: Robotics, Autonomous Mobility Robotics, Embedded Systems, Computational Intelligence Technique

- *Sept 2020 - Jun 2024*. [Beijing University of Chemical Technology](https://english.buct.edu.cn/main.htm), Beijing, CN
  - B.E. in Mechanical Design, Manufacturing and Automation, GPA: 3.62/4.33
  - Courses: Automatic Control Design, Artificial Intelligence, Mechine Design, Program Design, Hydraulic and Atmospheric Pressure Transmission 

# 🚀 Projects

<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <div class="badge">Senior Design</div>
    <img src="images/SeniorProject.gif" alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">


[**Robotics Senior Design at the University of Detroit Mercy**](https://youtu.be/Mp3_kLw8cQc)

- Designed an assistant robot system to help elderly individuals, combining mobile robots, computer vision, and a robotic manipulator.
- Modeled the *ReactorX-200* robotic arm and developed an app in *Matlab* to simulate both forward and inverse kinematics of the robotic arm. Finally, applied the algorithm to the real robotic arm for verification and used the program to control the arm.
- Trained dataset using *YOLOv8* and combined it with *Kinect V2* point cloud data to achieve target object localization.
- Performed camera calibration and hand-eye calibration between the robotic arm and the camera, significantly improving the grasping accuracy.
- Implemented navigation functionality using the *A\** algorithm for global path planning and the *DWA* algorithm for local path planning.
</div>
</div>



<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <div class="badge">RoboCup</div>
    <img src='images/DoorOpening.gif' alt="sym" width="100%">
    <img src="images/ObjectGrasping1.gif" alt="sym2" width="100%">
    <img src="images/ObjectGrasping2.gif" alt="sym2" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**RoboCup China Open 2022 ROBOCUP@HOME**

- Designed home service robot with capabilities in guest reception and guidance, object grasping & delivery, object recognition, and voice interaction.

- Designed and executed a algorithm combining object recognition with object grasping and delivery.

-	Orchestrated a four-step approach, including precise identification of target objects, accurate localization using depth cameras, pose analysis for gripping, and precise control of the robotic arm for successful object grasping and delivery.

-	Utilized *MoveIt* with *Open Motion Planning Library (OMPL)* for motion and path planning, *RRT\** algorithm for efficient trajectory generation, and *TRAC-IK* for accurate inverse kinematics.

-	Integrated *YOLOv5* and *Kinect DK* to achieve target object recognition and 3D localization.

- Used the *Grasp Pose Detection (GPD)* package to detect 6-DOF grasp poses for a 2-finger robot hand in 3D point clouds, enabling the grasping of objects in various orientations.

-	Successfully developed and implemented a unique robotic door-opening solution to complete the challenging task – the only team that completed this task.

-	Innovatively combined precise base positioning and mechanical arm path planning, significantly reducing computation time, streamlining the process, and efficiently completing door-opening tasks while ensuring obstacle avoidance.

- [Door-opening Solution](https://youtu.be/5L3_ih3M9L4)

- [Object Grasping ](https://youtu.be/INuuNCfpnjQ)

- [Receptionist](https://youtu.be/N8DXzzaAM7E)

- [What is That](https://youtu.be/Q4CnmgxCESk)

</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <img src='images/CarPole.gif' alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**RL Projects** 
- Complete the [CartPole](https://gymnasium.farama.org/environments/classic_control/cart_pole/) task in gym using the Actor-Critic Policy Gradient algorithm and the Deep Q-Network (DQN) algorithm, respectively.
- Successfully implemented playing [Frozen Lake](https://gymnasium.farama.org/environments/toy_text/frozen_lake/) using the Q-Learning algorithm.
</div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
  <div>
    <img src='images/AssemblyDrawing.jpg' alt="sym" width="100%">
  </div>
  </div>
<div class='paper-box-text' markdown="1">

**Other Projects** 
- [TM4C Microcontroller-based ROS Car](https://youtu.be/Vz4X8Z0HHWA)

- [Design of the Hydraulic System for a Single Leg Structure of a Multi-Legged Robot](https://github.com/TNA001-AI/Hydraulic-System-for-a-Single-Leg-Structure.git)

- [Genetic Algorithm Experiment and BP Neural Network Experiment](https://github.com/TNA001-AI/Genetic-Algorithm-Experiment-and-BP-Neural-Network-Experiment.git)

- [Two-stage gearbox mechanical design](https://github.com/TNA001-AI/Two-stage-gearbox-mechanical-design)

</div>
</div>

# 💻 Internships
- *Feb 2023 - May 2023*, Tsinghua University Intelligent Connected Vehicle Research Group, Beijing, China.
  - Developed a system integrating electric truck fleet scheduling and battery swapping optimization with cloud control, enhancing efficiency and reducing energy waste. In simulation experiments, using this algorithm saves $15\%$ more energy and $9\%$ more cost compared to the *Cruise Control (CC)* method.
  - Created a *Predictive Cruise Control (PCC)* for cruise control in electric trucks. Factored in road slope information and used the *Dynamic Programming (DP)* algorithm to generate efficient speed sequences, reduce energy consumption, and enhance energy regenerative capabilities.
  - Implemented cloud control for real-time fleet, environment, and infrastructure connectivity, improving adaptive driving with dynamic traffic data by using the *Genetic Algorithm (GA)*.
  - Co-authored a patent on *Battery Swapping Rhythm Planning and Predictive Cruise Control Method for Electric Heavy Truck Fleets* (Patent Number: [CN117002500A](http://epub.cnipa.gov.cn/patent/CN117002500A)).

# 🏆 Honors and Awards
- *Jan 2023*, Individual Scholarship in School Year 2021-2022 Term 2 in BUCT
- *Nov 2022*, **National First Prize in 2022 RoboCup China Open ROBOCUP@HOME**
-	*Nov 2022*, **Second Prize in 2021 China Robot Skills Competition, Beijing Division A Group**
- *Nov 2022*, Qualified in the program Intelligent Four-legged Voice Interactive Robot in 2022 Innovation and Entrepreneurship Training Program for college students
-	*Nov 2022*, Qualified in the program Humanoid Soft Robot in 2022 Innovation and Entrepreneurship Training Program for college students
-	*May 2022*, Third Scholarship in School Year 2021-2022 Term 1 in BUCT
-	*Dec 2021*, **National Second Prize in 2021 China Robot Skills Competition**
-	*Dec 2021*, Third Scholarship in School Year 2020-2021 Term 2 in BUCT
-	*Jul 2021*, Third Prize in 2021 BUCT Intelligent Service Robot Competition
-	*May 2021*, Third Scholarship in School Year 2020-2021 Term 1 in BUCT
-	*Apr 2021*, Outstanding Student Leader in BUCT CEE

# 🧠 Skills

- **Programming Language**: Proficient in using *C++*, *Python*, and *Matlab* in robotics. 
- **ROS**: Proficient in working with *ROS*.
- **Robotics and Robot Control**: Proficiency in using robotics control frameworks like *MoveIt* for motion planning. Skill in kinematics solving.
- **Navigation and Mapping**: Advanced skills in 2D indoor mapping using tools like *Google Cartographer*. Implementation of path planning algorithms and tools, including *DWA, RRT, A\*, Move_Base*, etc.
- **Cloud-Based Vehicle Control**: Hands-on experience in developing cloud-based control systems for vehicles. Algorithm development for optimizing vehicle speed and power management.
- **Microcontroller Proficiency**: Proficient in the use of *TM4C* microcontrollers and *Arduino*.
- **Mechanical Design**: Proficient in manual engineering drawing and using *SolidWorks* for mechanical design, having completed multiple mechanical design projects.
- **Mathematical Modeling**: Deep understanding of mathematical modeling methods and tools. Application of mathematical modeling principles in real-world problem-solving.
- **Soft skills**: Quick learning ability, self-starting, and problem-solving as demonstrated in numerous competitions and internships.





