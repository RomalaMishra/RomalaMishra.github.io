---
layout: archive
title: "A few of the projects I worked on!"
permalink: /project/
author_profile: true
redirect_from:
  - /extracurricular-activities
---
## Smart Glasses for the visually and hearing impaired
*Project Member: Romala Mishra*

In this project, I developed a multimodal assistive system for individuals who are visually or hearing impaired by combining embedded hardware with deep learning-based visual perception. Using an Arduino Uno, I interfaced ultrasonic sensors to detect obstacles in three directions. These signals were transmitted to a Raspberry Pi, which provided real-time auditory alerts through a Bluetooth speaker — enabling spatial awareness for visually impaired users. To assist users who are deaf or hard of hearing, I deployed a CNN–Transformer-based gesture recognition model on the Raspberry Pi. This model processed live camera input using OpenCV, TensorFlow, and Python to interpret sign language gestures. When a deaf user performs gestures in front of the camera (e.g., mounted on smart glasses), the system can convert them to spoken output via the speaker, allowing communication with hearing individuals who do not understand sign language. The system demonstrates the potential of lightweight, real-time AI for enhancing accessibility through multimodal assistance.[[Code]](https://github.com/RomalaMishra/Smart_Glasses).

## Intelligent Ground Vehicle 
*Project Member: Romala Mishra*

I developed a novel and lightweight U-Net-based deep learning model for accurate and real-time lane segmentation tailored to autonomous ground vehicle systems. The model was trained using lane annotations extracted from ROSBag files and optimized for deployment in real-world navigation scenarios. To ensure low-latency performance, I integrated the trained network on an NVIDIA Jetson Nano, enabling efficient on-board inference suitable for embedded robotic platforms. This work demonstrates the potential of compact semantic segmentation models in supporting autonomous navigation through precise lane perception.

## Vacbot - Autonomous Cleaning Bot
*Project Members: Romala Mishra, Pratik Kumar Sahoo, Mrinal Misra*

We developed an autonomous cleaning robot simulation equipped with SLAM (Simultaneous Localization and Mapping) to enable real-time area exploration and understanding of dynamic environments. The system utilized RRT (Rapidly-exploring Random Tree) for efficient global path planning, allowing the robot to systematically explore and map previously unmapped regions. To ensure safe and smooth navigation, I integrated MoveBase with local costmaps and a dynamic planner, enabling real-time, obstacle-aware path execution and collision-free movement throughout the environment. This project demonstrated the coordinated use of perception, planning, and control modules in a robotics simulation for autonomous navigation tasks.[[Code]](https://github.com/RomalaMishra/vacbot).

## Holonomic Art Bot 
*Project Members: Romala Mishra, Pratik Kumar Sahoo, Shantanu Panda, Monalisa Behera*

We designed and implemented the controller logic for a 3-omni-wheel holonomic robot, enabling smooth and precise omnidirectional movement. The system extracted contour points from a given sketch, converting them into coordinate-based waypoints that defined the robot’s drawing trajectory. For global localization, an overhead camera was employed along with ArUco markers, allowing the robot to track its position in real-time. Using PID control and inverse kinematics, we computed individual wheel velocities to ensure accurate path following and faithful sketch rendering, demonstrating the integration of vision-based localization, motion planning, and control in a real-world robotic system.[[Code]](https://github.com/RomalaMishra/eyrc22_HB_1570).


## Mini Projects:
****************************************
### A list of small projects which required less than a week to work on:
* **Epileptic Seizure Detection using EEG Signals**: This project explores the detection of epileptic seizures using EEG (Electroencephalogram) signals, applying both a simple Artificial Neural Network (ANN) and a hybrid CNN-ANN model.[[Code]](https://github.com/RomalaMishra/EpilepticSeizure-EEG).

* **Path Planning Algorithms Visualizer**: This project demonstrates and compares classical path planning algorithms — A*, Dijkstra, Breadth-First Search (BFS), and Depth-First Search (DFS) — on a 2D grid. It visualizes the path generated by each algorithm and compares them based on execution time and path length.[[Code]](https://github.com/RomalaMishra/pathplanning_analysis).

* **Face Detection Algorithms**: This project focuses on implementing and evaluating various face detection algorithms using Python and computer vision libraries. The goal is to detect faces within images or video streams and, in some cases, identify facial landmarks or attributes.[[Code]](https://github.com/RomalaMishra/Multimodal-Face-Detection-Algorithms).

* **UAgents-weather**: The TemperatureX Web Application is a Flask-based Temperature Alert Agent built using Fetch.AI's uAgent library that provides a simple interface for users to input their desired location and temperature range and then displays real-time temperature status updates on the webpage, i.e., sends alert/notification to the user when the current temperature in their chosen location goes below the minimum or above the maximum threshold they've set.[[Code]](https://github.com/RomalaMishra/UAgents-weather).

* **Air Canvas**: This project allows users to draw and create art in a virtual canvas using their hand gestures. It combines computer vision techniques(OpenCV and mediapipe library) to recognize hand gestures and detect objects on the canvas.[[Code]](https://github.com/RomalaMishra/Air_Canvas).

* **Automatic Volume and Brightness Control**: This project provides an automatic control system for adjusting the volume and brightness of a device using hand recognition. It uses computer vision techniques(mediapipe) to detect and track hand gestures, allowing users to interact with their device without physically touching it.[[Code]](https://github.com/RomalaMishra/Volume_control).



  