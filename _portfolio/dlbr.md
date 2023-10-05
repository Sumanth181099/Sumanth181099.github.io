---
title: "Deep Learning Based Localization and Control of Indoor Robots"
#excerpt: "Our solution to the CVPR Perception Beyond Visible Spectrum Workshop 2022: Multi-Modal Aerial View Object Classification challenge. We proposed a novel Multi-Modal Domain Fusion(MDF) network to learn the domain invariant features from multi-modal data and use it to accurately classify the aerial view objects<br/><a href="https://arxiv.org/pdf/2212.07039.pdf">paper</a>    <a href="https://github.com/Sumanth181099/PBVS_MAVOC2022">code</a><br><img src='/images/Screenshot from 2023-10-05 19-16-19.png'>"

collection: portfolio
---
<table style="border-collapse: collapse; border: none; font-size:16px">
<tr style="border: none;">
<th style="border: none;"><img src="/images/Screenshot from 2023-10-05 20-09-06.png" width="100%" height="100%"/></th>
<th style="border: none; ">Tackled the perception and control of an autonomous robot working in an indoor environment.<br>
<a href="https://drive.google.com/file/d/1hynRl29z6ciSxhXPUYXFY83fgWyJzXKo/view">Report</a>    <a href="https://github.com/Sumanth181099/Deep-Learning-Based-Localization-of-a-Robot-">code</a><br>

</th>
</tr>
</table>

Autonomous Systems involves three main aspects: Perception, Action/Navigation and control of the system under inspection. In this work, we have tackled the perception and control of an autonomous robot working in an indoor environment. In the initial section we will describe the design of the robot, the kinematics and dynamics equations used to model the designed robot. The mechanical modelling was done using SolidWorks software while the mathematical modelling was done using MATLAB. The control approach used to navigate the robot as per the paths required is done by a high level controller sending commands to a low level controller. In the main section we will describe the perception aspect, that is the localization aspect of the system. We use a CNN-LSTM based network to localize our robot. ROS and Gazebo was used extensively to build our custom dataset.
