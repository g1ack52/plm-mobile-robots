# 🤖 Perception, Localization and Mapping for Mobile Robots

This repository contains two projects developed for the course **Perception, Localization and Mapping for Mobile Robots**.

All code is written in **C++** using the **Robot Operating System (ROS)** framework.  
Each project is self-contained and includes launch files, configuration files, and ROS nodes.

---

## 📌 First Project: Odometry and Sector Analysis

We developed three ROS nodes to compute:

- **Odometry from steering data**
- **Odometry from GPS coordinates**
- **Sector times and average speed**

The system processes real driving data to estimate the car's trajectory and performance on a predefined circuit.  
It includes a full launch file with `rviz` configuration to visualize odometry and trajectory in real-time.

---

## 🗺️ Second Project: Mapping and Navigation

This project focuses on:

- **Creating a 2D map** using raw laser scan and odometry data from a mobile robot
- **Simulating robot navigation** using `stage` and ROS Navigation Stack

The laser scans from front and rear sensors are combined into a 360° view and filtered to exclude parts of the robot itself.  
A navigation pipeline is implemented to drive the simulated robot through a sequence of goals defined in a CSV file.

---

## 📁 Project Structure

