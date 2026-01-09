
# 🤖 Mobile Bot – ROS 2 URDF Visualization

This project showcases the design and visualization of a **simple mobile robot** created using **ROS 2 Humble** and **URDF**, and visualized in **RViz**.

The focus of this project is to understand **robot structure, joints, and TF frames** in ROS 2 through a hands-on mobile robot model.

---
<p align="center">
  <img src="mobile_bot/mobile_bot_zoom.png" height="260"/>
  <img src="mobile_bot/mobile_bot.png" height="260"/>

</p>



## 📌 Project Overview

In this project, I built a **basic mobile robot** consisting of:

• A rectangular base body  
• Two rotating wheels (left and right)  
• A caster wheel for stability  
• A rotating LiDAR sensor mounted on top  
• Proper parent–child joint relationships  

The robot is visualized using:

• RobotModel  
• TF  
• Joint State Publisher  

This project is ideal for beginners learning **URDF and robot visualization**.

---

## 🧱 Robot Structure

### 🔴 Base Link
• Main body of the robot  
• All other components are attached to this link  

### 🔵 Wheels
• Two side wheels for motion  
• Connected using continuous joints  
• Rotation visible in RViz  

### ⚪ Caster Wheel
• Fixed caster wheel  
• Provides balance and support  

### 📡 LiDAR Sensor
• Mounted on the top of the robot  
• Rotates about the Z-axis  
• Helps understand sensor mounting  

---

## 🧭 Frames and Visualization

• Each link has its own coordinate frame  
• ROS axis convention:  
  - Red → X axis  
  - Green → Y axis  
  - Blue → Z axis  

• TF display shows link relationships  
• Grid enabled for spatial reference  

---

## 🎯 What I Learned

• Building robot structure using URDF  
• Understanding links and joints  
• Difference between fixed and continuous joints  
• Visualizing TF frames in RViz  
• Using Joint State Publisher for testing motion  
• Basics of mobile robot design  

---

## 🛠 Tools and Technologies

• ROS 2 Humble  
• URDF  
• RViz  
• TF  
• Joint State Publisher  

---

## 🚀 Future Improvements

• Add collision and inertial properties  
• Simulate the robot in Gazebo  
• Implement differential drive control  
• Add sensor plugins  
• Control the robot using cmd_vel  

---

## 👤 Author

**M P Nithish Praba**  
ROS 2 Learner | Robotics Enthusiast

