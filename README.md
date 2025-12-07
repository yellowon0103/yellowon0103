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

| Category | Skills |
| :--- | :--- |
| **Core** | Python, C++, C# |
| **AI / Vision** | PyTorch, OpenCV, OpenGL, Open3D, Blender, MeshLab |
| **Robot / AR / VR** | Arduino, Unity, SLAM, HTC VIVE, Meta Quest |



## 💼 Experience

### Korea Institute of Science and Technology (KIST)
*Seoul, South Korea*

**Graduate Student Researcher | AI & Robotics Institute**
> *Mar 2024 – Present*
- **Focus**: **Monocular RGB Dynamic SLAM**
- Research on deep learning-based SLAM systems in dynamic environments.
<img src="./assets/anymal2.png" width="500">

**Undergraduate Research Intern | AI & Robotics Institute**
> *Jun 2023 – Dec 2023*
- **Focus**: **3D Human Head Modeling**
- Preprocess data for large-scale 3D multi-view facial datasets to ensure model training quality.
<img src="./assets/image (11).png" width="500">


## 📜 Projects & Research

### [2024] Master's Coursework Projects

**1. 3D Reconstruction from Sparse-view Pose-Free Images**
- **Course**: Artificial Intelligence
- **Description**: Reconstructed 3D scenes from sparse images without camera pose information using deep learning models.
<img src="./assets/image (10).png" width="500">

**2. 3D Mesh & Point Cloud Viewer**
- **Course**: Visual Computing
- **Tech**: C++, OpenGL
- **Description**: Developed a viewer to visualize 3D Meshes and Point Clouds.
<img src="./assets/image (4).png" width="500">

**3. Adaptive Hand Gesture Implementation**
- **Course**: Basics of VR/AR
- **Tech**: Unity
- **Description**: Implemented a system where hand gestures change adaptively based on the size of virtual objects.
<img src="./assets/image (5).png" width="500">

### [2023] Award & Paper & Undergraduate Project

**1. Haptic Interface for AR/VR Realism 🏆**
- **Award**: **Excellence Award** (Hongik Univ. Graduation Exhibition)
- **Role**: Development of a haptic interface maximizing realism and gesture application.
- **Description**: Created a wearable device to enhance immersion in AR/VR environments.
- **Links**: [🔗Demo](https://www.youtube.com/watch?v=-RJZX_VnEtY) <- 6분 23초부터 시연영상입니ㅏㄷㅇ
<img src="./assets/image (3).png" width="500">
<img src="./assets/image (9).png" width="500">

**2. Feeling the Hit: Haptic Impact for Realistic Virtual Punch 📝**
- **Type**: Research Project (Submitted to VRST 2023)
- **Description**: Proposed and experimented with a haptic interface that provides realistic impact feedback for virtual punching interactions.
- **Links**: [🔗Paper](https://drive.google.com/file/d/1xLS96gyyfeGryjI3FT78jPWnHXA1y16Y/view?usp=sharing)
<img src="./assets/image (2).png" width="500">
<img src="./assets/image (1).png" width="500">
<img src="./assets/image (8).png" width="500">

**3. Metaverse Marketplace "Carrot Market Pro"**
- **Course**: Computer Graphics & Metaverse
- **Tech**: LiDAR, Unity
- **Description**: Built a metaverse platform utilizing LiDAR scans to upload and view real-world items for second-hand trading.
<img src="./assets/image (7).png" width="500">

### [2022] Conference Paper 

**Wearable Haptic System for Car Navigation 📝**
- **Publication**: The Korean Society of Mechanical Engineers (KSME) Autumn Conference
- **Description**: Proposed a wearable haptic system to provide navigation cues to drivers.
- **Links**: [🔗Paper](https://www.dbpia.co.kr/journal/articleDetail?nodeId=NODE11183222)
<img src="./assets/image.png" width="500">

### [2021] Award

**Android RPG Escape Game using Unity 🏆**
- **Award**: **Silver Award** (Hongik Univ. Project Competition)
- **Description**: Developed an Android-based RPG escape game featuring puzzle elements and storytelling.
- **Links**: [🔗Paper](https://github.com/cwj980119/Unity-Escape_T)
<img src="./assets/image (6).png" width="500">

---
### 📫 Contact
- **Email**: gyw1teens@gmail.com
- **LinkedIn**: www.linkedin.com/in/yewon-kim-6a8a20366
- **Location**: Seoul, South Korea
