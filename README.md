<div align="center">

# Hariram Sampath Kumar

### Intelligent Field Robotics · Vision-Language AI · Autonomous Systems

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://linkedin.com/in/Hariram-Sampath-Kumar)
[![Email](https://img.shields.io/badge/Email-EA4335?style=flat&logo=gmail&logoColor=white)](mailto:s.hariram1001@gmail.com)
[![Google Scholar](https://img.shields.io/badge/Google_Scholar-4285F4?style=flat&logo=googlescholar&logoColor=white)](https://scholar.google.com/citations?user=5X3hs8QAAAAJ&hl=en)
[![Profile Views](https://komarev.com/ghpvc/?username=ByteMastee&color=0e75b6&style=flat&label=Profile+Views)](https://github.com/ByteMastee)

*Budapest, Hungary*

</div>

---

## About

I started in **Mechatronics Engineering** — building swarm robots from scratch with microcontrollers, IR/PIR sensors, and inter-robot transceivers, programming CNC machines with Arduino, and working with PLC automation systems. That foundation in hardware-software integration pushed me toward AI, where I worked on computer vision pipelines, GAN-based super-resolution, and nature-inspired optimization.

Today, I am an **ERASMUS MUNDUS IFRoS scholar** (UdG, Spain & ELTE, Hungary) — one of the most competitive fully-funded robotics master's programmes in Europe. My current work at **EUROKNOWS, Hungary** proposes and evaluates three progressively complex semantic mapping pipelines for mobile robotics — integrating object detection, segmentation, and vision–language models for context-aware scene understanding and natural-language interpretation in real-world environments.

Across this journey I have implemented systems end-to-end: from bare-metal embedded code to deep learning training pipelines, from kinematic controllers to EKF-SLAM, from path planners to speech-driven robot navigation — always on real or simulated hardware, always in ROS.

---

## What I Have Built

- **Autonomous field robots** — swarm intelligence (PSO), embedded microcontrollers, IR/PIR sensing, inter-robot transceiver communication
- **CNC & automation systems** — Arduino-based X-Y plotter, PLC programming with CoDeSys, industrial robot manipulation with CIROS
- **Deep learning models** for super-resolution and object detection
- **Nature-inspired optimization frameworks** for urban infrastructure planning using GIS data
- **Perception & Navigation pipelines** for mobile robots — RGB-D, LiDAR, ArUco, EKF-SLAM
- **Kinematic controllers** for mobile manipulators using task-priority redundancy resolution
- **Kinodynamic planners** combining RRT, spline smoothing, and Pure Pursuit control
- **Vision–Language systems** for semantic scene understanding and instruction grounding

---

## Tech Stack

<div align="center">

**Robotics & Simulation**

![ROS](https://img.shields.io/badge/ROS-22314E?style=flat&logo=ros&logoColor=white)
![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat&logo=ros&logoColor=white)
![Gazebo](https://img.shields.io/badge/Gazebo-FF6600?style=flat&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat&logo=linux&logoColor=black)

**AI & Computer Vision**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat&logo=tensorflow&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat&logo=opencv&logoColor=white)

**Engineering & Embedded**

![C++](https://img.shields.io/badge/C++-00599C?style=flat&logo=cplusplus&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat&logo=arduino&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-0076A8?style=flat&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)

</div>

---

## Selected Projects

### 🗣️ [OTNav — Speech-Commanded Object Navigation](https://github.com/IFRoS-ELTE/OTNav)
A mobile robot that receives spoken commands (*"go to the red chair"*), detects and localizes the object in 3D using RGB-D + YOLO, and navigates safely — with active frontier-based search if the object is not visible. Built on AgileX SCOUT Mini with ROS, running end-to-end in real-time.

### 🤖 Mobile Manipulator — Task-Priority Kinematic Control
Full pick-and-place system on TurtleBot2 + uArm Swift Pro using hierarchical null-space control, ArUco marker detection, and dead reckoning. 11 sequentially ordered tasks executed autonomously in Stonefish simulation.

### 📍 Bearing-Only EKF-SLAM (FEMKSLAM)
Lightweight SLAM fusing odometry, IMU, and bearing-only ArUco observations. Demonstrated robust re-localization after deliberate high-speed drift and wall collision — map orientation remained accurate throughout.

### 🗺️ Kinodynamic Frontier Exploration Planner
RRT + tensioned B-spline smoothing + Pure Pursuit controller for continuous forward-motion exploration of unknown maps. Achieved full coverage in 65.7% of 35 simulation runs with under 1 forced stop per run on average.

### 🔬 Urban Rail Network Optimization · [Taylor & Francis 2024](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003530190-25/) · [arXiv](https://arxiv.org/abs/2407.17508)
AI-driven optimization framework for urban rail network planning integrating GIS spatial data with nature-inspired algorithms (PSO, GA). Evaluated across real urban landscape datasets and published as a Taylor & Francis book chapter.

### 🛰️ Super-Resolution for Aerial Imagery · [IEEE ICCSC 2024](https://ieeexplore.ieee.org/abstract/document/10830430)
GAN-based super-resolution architecture benchmarked against existing works on aerial military imagery datasets — outperformed state-of-the-art on PSNR/SSIM metrics.

### 🤖 Intelligent Swarm Robots for Surveillance
5 autonomous field robots with PSO-based swarm intelligence, IR/PIR sensing, and transceiver-based inter-robot communication. Bachelor's dissertation — state-funded research grant recipient.

---

## Publications

[![IEEE](https://img.shields.io/badge/IEEE-00629B?style=flat&logo=ieee&logoColor=white)](https://ieeexplore.ieee.org/abstract/document/10830430)
[![arXiv](https://img.shields.io/badge/arXiv-B31B1B?style=flat&logo=arxiv&logoColor=white)](https://arxiv.org/abs/2407.04087)
[![Taylor & Francis](https://img.shields.io/badge/Taylor_%26_Francis-0C2340?style=flat&logoColor=white)](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003530190-25/)

- **Generation of Super-Resolved Images Using Deep Neural Networks** — [IEEE ICCSC 2024](https://ieeexplore.ieee.org/abstract/document/10830430)
- **Advanced AI Strategy for Urban Rail Network Design using Nature-Inspired Algorithms** — [Taylor & Francis 2024](https://www.taylorfrancis.com/chapters/edit/10.1201/9781003530190-25/) · [arXiv](https://arxiv.org/abs/2407.17508)
- **AI Based Navigation in Quasi Structured Environment** — [arXiv 2023](https://arxiv.org/abs/2407.04087)

---

## GitHub Stats

<div align="center">

![Hariram's GitHub Stats](https://github-readme-stats.vercel.app/api?username=ByteMastee&show_icons=true&theme=dark&hide_border=true&title_color=58a6ff&icon_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)
&nbsp;&nbsp;
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ByteMastee&layout=compact&theme=dark&hide_border=true&title_color=58a6ff&text_color=c9d1d9&bg_color=0d1117)

</div>

---

<div align="center">

*Erasmus Mundus Scholar · IEEE Published · State-Funded Researcher · Smart India Hackathon 2022 Finalist*

</div>
