# SELQIE-The Seafloor Environment Legged Quadruped Intelligent Explorer

The seafloor is a complex environment and it is challenging to conduct detailed mapping, soil composition sampling, and habitat characterization missions in this benthic region. As a step toward overcoming these challenges, we present a quadruped robot capable of walking on the seafloor and maneuvering via mid-fluid swimming. SELQIE, the Seafloor Environment Legged Quadruped Intelligent Explorer, is capable of walking underwater at speeds up to 0.2 m/s, swimming at over 0.16 m/s, and transitioning between modes. We also introduce a path planning algorithm that can account for both swimming and walking gaits to efficiently navigate around or over obstacles, and demonstrate the robot executing such a multi-modal trajectory.

I was the project lead on SELQIE, overseeing the design of the physical system, electronic integration, code integration, and experimental validation. I worked primarily with the mechanical design team to improve upon the STARQ quadruped and make modifications for an underwater walking system. The platform is also capable of 3rd degree of freedom iterations. (More seen in platform section). I assisted in the electronic documentation and integration, as well as learned the code infrastructure in order to operate and debug SELQIE. 

## 📄 Quick Links! 

View the ICRA paper <a href="https://ieeexplore.ieee.org/document/11127516">**HERE** </a>.


## 🤖 The Platform
![ss](https://github.com/AshETQ/SELQIE-Overview/blob/d4d2115b039e4b27617610ad009774c6898d3959/Images/OverviewNoPNU1.png)

SELQIE is able to walk underwater, swim midfluid, and transition between the two modes with the same limbs and code base! <a href="https://github.com/JTylerBoylan" target="_blank">**Jonathan Boylan** </a> also incorporated autonomy into SELQIE, seen further on his GitHub. For testing, SELQIE is driven through ROS commands or through joystick. A comparison of the SBMPO look at the least distance path is below. SELQIE was created to navigate underwater obstacles underwater, and is equipped with a full vision suite and multi-modal functions to achieve that goal. 

![ss2](https://github.com/AshETQ/SELQIE-Overview/blob/d4d2115b039e4b27617610ad009774c6898d3959/Images/ObstacleCourse_2.png)
![ss3](https://github.com/AshETQ/SELQIE-Overview/blob/d4d2115b039e4b27617610ad009774c6898d3959/Images/RobotOverview2.png)

Further results can be seen in the paper, and the figures of results within in the Images folder here. 

## 🎥 In Action! (Uploading soon)

See how SELQIE moves! Underwater obstacle course and real world environment (Wacissa River) videos located <a href="https://1drv.ms/f/c/8fdf2d1a8c790b06/IgDY-ApfERH_TpW1cBjkiztXAYM_40pI5uK0lfvsnyvQ5d0?e=2jZTr7" target="_blank">**HERE** </a>.

## 💬 Presentation Mode

This work was presented at ICRA 2025! 
![ss4](https://github.com/AshETQ/SELQIE-Overview/blob/d4d2115b039e4b27617610ad009774c6898d3959/Images/icrapresent.jpg)


## 💻 Code

SELQIE operating code is not currently available to public. ROS2 with joystick control and autonomy. Autonomy focus and infrastructure created by <a href="https://github.com/JTylerBoylan" target="_blank">**Jonathan Boylan** </a>. Maintained through a private directory on GitHub. Physical robot located at FSU STRIDe Lab. 

