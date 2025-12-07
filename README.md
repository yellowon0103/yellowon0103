# 👋 Hello, I'm Yewon Kim
### 3D Vision & SLAM Researcher | Master's Student at Korea University

I am passionate about bridging the gap between the physical and digital worlds through **3D Vision** and **Deep Learning**. 

My research focuses on building robust SLAM systems for dynamic environments and real-time applications.

## 📺 Project Demo : Real-time RGB Dynamic SLAM with Pixel-wise Motion Masking
[![Demo Video](./assets/Bonn_dynamic_visualize.png)](https://youtu.be/Kaef6XRzZyU)


> 🚨 **Click the image above to watch the demo video!**


**1. Problem: Limitations of Object-level Masking**
In online SLAM systems, ensuring **Tracking Stability** is critical to maintain continuous camera localization. 
Existing **Object-level masking methods** tend to remove entire dynamic objects, even when parts of them remain static. While this approach may be advantageous for reconstruction, it leads to **Feature Starvation** in crowded scenes where dynamic objects dominate the field of view. This depletion of matching information often results in immediate **Tracking Failure** and frequent **Relocalization**.

**2. Solution: Pixel-wise Motion Masking**
To address this, I proposed **Pixel-wise Motion Masking**, a method that goes beyond simple object removal by identifying and masking only the pixels that are actually moving at the current moment.
- **Methodology**: By integrating **Dense Geometric Prior (DUSt3R)** with **Dense Point Tracking (All-Tracker)**, the system precisely identifies dynamic pixels based on the discrepancy between scene flow and point tracking.
- **Tracking Stability**: This approach actively utilizes **Temporarily Static Parts** within dynamic objects as valid matching features. This maximizes the number of effective tracking points, ensuring stability even in highly dynamic environments.

**3. Performance**:
Unlike existing State-of-the-Art (**WildGS-SLAM**, Dec 2025) methods that are limited to **0.5–2 FPS**, this system achieves **real-time performance of over 15 FPS**.


## 🛠 Tech Stack
- **Core**: Python, C++, C#
- **AI/Vision**: PyTorch, OpenCV, OpenGL, Open3D, Blender, MeshLab
- **Robot/AR/VR**: Arduino, Unity, SLAM, HTC VIVE, Meta Quest

## 🛠 Tech Stack

| Category | Skills |
| :--- | :--- |
| **Core** | Python, C++, C# |
| **AI / Vision** | PyTorch, OpenCV, OpenGL, Open3D, Blender, MeshLab |
| **Robot / AR** | Arduino, Unity, SLAM, HTC VIVE, Meta Quest |

<br>


## 🚀 Projects

## 💼 Experience

### Korea Institute of Science and Technology (KIST)
**Graduate Student Researcher | AI & Robotics Institute**
- **Period**: Mar 2024 – Present
- **Monocular RGB Dynamic SLAM**: Research on deep learning-based SLAM systems in dynamic environments.

### Korea Institute of Science and Technology (KIST)
**Undergraduate Research Intern | AI & Robotics Institute**
- **Period**: Jun 2023 – Dec 2023
- **3D Human Head Modeling**: Contributed to high-fidelity 3D avatar generation technology.

## 📜 Projects & Publications

### [2024] Master's Coursework Projects
**1. 3D Reconstruction from Sparse-view Pose-Free Images**
- **Course**: Special Topics in Artificial Intelligence
- **Description**: Generated point clouds and rendered novel views from just two images using Dust3r. Implemented reference-based inpainting (LeftRefill) for occluded areas to reconstruct scenes without camera poses.

**2. 3D Mesh & Point Cloud Viewer**
- **Course**: Visual Computing
- **Tech**: C++, OpenGL
- **Description**: Developed an interactive viewer to visualize depth maps from Dust3r/Geowizard as point clouds and mesh.

**3. Hand Gesture Implementation for Virtual Objects**
- **Course**: Basics of VR/AR
- **Tech**: Unity
- **Description**: Implemented a system where hand gestures adapt dynamically based on the size of virtual objects.

### [2023]
**1. Haptic Interface for AR/VR Realism (Graduation Exhibition)**
- **Award**: Honorable Mention
- **Role**: Unity VR Environment Development & Communication (Serial/Socket)
- **Description**: Developed a wearable haptic interface using bending sensors and LRA vibration motors to control objects and provide feedback in VR, overcoming vision-based tracking limitations.

**2. Feeling the Hit: Haptic Impact for Realistic Virtual Punch**
- **Submission**: VRST 2023 (Paper)
- **Role**: Unity VR Development & Haptic Experiment Setup
- **Description**: Proposed a haptic interface rendering realistic impact sensations by physically contacting a real object synchronized with a virtual punch.

**3. Metaverse "Danggeun Market Pro" using LiDAR**
- **Course**: Computer Graphics & Metaverse
- **Tech**: LiDAR Scanning (Polycam), Unity
- **Description**: Built a metaverse commerce platform where users can inspect 3D-scanned second-hand items in a virtual environment before trading.

### [2022]
**Wearable Haptic System for Car Navigation**
- **Publication**: The Korean Society of Mechanical Engineers (KSME) Spring/Autumn Conference
- **Role**: Unity 3D Driving Environment & Arduino Haptic Control
- **Description**: Designed a skin-stretch haptic navigation system to deliver directional information to the driver's arm, reducing visual distraction.

### [2021]
**Android RPG Escape Game using Unity**
- **Award**: Silver Award (Hongik Univ. Project Competition)
- **Role**: UI/UX Development & Interaction Logic (C#)
- **Description**: Developed a mobile RPG creating a virtual campus for students unable to visit due to COVID-19. Implemented touch-based puzzles, NPC interactions, and modularized code for maintenance.

---
### 📫 Contact
- **Email**: gyw1teens@gmail.com
- **LinkedIn**: www.linkedin.com/in/yewon-kim-6a8a20366
- **Location**: Seoul, South Korea
