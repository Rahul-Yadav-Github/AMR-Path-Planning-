
# 🦾 AMR Path Planning Optimization in ROS 2

This repository contains the project files for the B.Tech. Project:

**“AMR Path Planning Optimization: Layout Comparison & Energy Analysis”**  
from the **Indian Institute of Technology Ropar**.

---

## 📘 Overview

This project focuses on developing and evaluating **path planning optimization strategies** for **Autonomous Mobile Robots (AMRs)** in warehousing and vertical farming environments.

It compares **three distinct warehouse layouts** and **three path planning algorithms** to analyze **travel distance** and **energy consumption**.

### 🏗️ Layouts
- Grid  
- Fishbone  
- Serpentine  

### 🧭 Algorithms
- A*  
- RRT*  
- D* Lite  

---

## 🧰 Tech Stack

| Component | Description |
|------------|-------------|
| **Framework** | ROS 2 Jazzy |
| **Simulation** | Gazebo 11 |
| **Visualization** | RViz |
| **Robot Model** | Novus Carry AMR |
| **Operating System** | Ubuntu 24.04.3 LTS |
| **Languages** | Python, C++ (for ROS nodes), XML (for launch/config) |
| **Analysis Tools** | Python (Pandas, Matplotlib) |

---

## ✨ Features

### 🏭 1. Warehouse Layouts
Gazebo world files for **Grid**, **Fishbone**, and **Serpentine** layouts.

### 🧩 2. Path Planning Algorithms
ROS 2 node implementations for:
- **A\***
- **RRT\***
- **D\* Lite**

### ⚙️ 3. Energy Analysis
Python scripts for:
- Data collection  
- Analysis of **travel distance**, **time**, and **energy usage**

### 🚙 4. Realistic Simulation
Incorporates the **Novus Carry AMR model** with **LIDAR-based navigation** for realistic motion and sensing.

---

## 🛠️ Setup and Installation

### Prerequisites

Ensure the following are installed:

- **Ubuntu 24.04.3 LTS**
- **ROS 2 Jazzy** (follow [official installation guide](https://docs.ros.org/en/jazzy/Installation.html))
- **Gazebo 11**
- **Python 3.8+**

### Install Python Packages
```bash
pip install pandas matplotlib
````

---

## 👥 Project Team

| Name            | Roll Number | Role              |
| --------------- | ----------- | ----------------- |
| **Rahul Yadav** | 2022MEB1334 | Project Developer |
| **Sumer Bassi** | 2022MEB1351 | Project Developer |

### 🧑‍🏫 Supervisor

**Dr. Ekta Singla**
Department of Mechanical Engineering
**Indian Institute of Technology Ropar**

---

## 📜 License

This project is licensed under the **MIT License**.
You are free to use, modify, and distribute this project with proper attribution.

