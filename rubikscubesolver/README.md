## 🟥 Rubiks Cube Solver: Computer Vision & Mixed Reality Framework

> **"A project at the convergence of vision science, optimization algorithms, and augmented reality. The goal is to detect, solve, and overlay the optimal solution path directly onto a physical Rubik's Cube in real-time."**

## Overview

The **Rubiks Cube Solver** is a technical showcase designed to demonstrate the power of integrating complex computational theory with real-time computer vision and immersive mixed reality (MR) interfaces.

It transforms a common physical puzzle into a sophisticated software problem, covering the full pipeline: **State Acquisition (Vision) $\rightarrow$ Optimal Pathfinding (Algorithm) $\rightarrow$ User Guidance (Augmented Reality).**

---

## 🛠️ Architecture and Pipeline

The system is split into three highly specialized, modular components:

### 1. Vision & State Detection (The Input Layer)
* **Purpose:** To reliably determine the scrambled state of the physical cube using a standard device camera (mobile or webcam).
* **Challenges:** Dealing with varied lighting conditions, reflections, camera perspective distortion, and achieving accurate color segmentation on all six faces simultaneously.
* **Key Tasks:**
    * **Real-time Cube Detection:** Locating and tracking the cube in 3D space.
    * **Color Calibration:** Normalizing colors to reliably identify the 54 unique facelets.
    * **State Encoding:** Translating the visual data into a standardized, machine-readable format (e.g., Kociemba notation).

### 2. Algorithmic Solver Core (The Cognitive Layer)
* **Purpose:** To find the shortest, most efficient sequence of moves required to solve the detected cube state.
* **Algorithm:** Implementation of an efficient two-phase search algorithm (e.g., Kociemba's algorithm or an optimized breadth-first search variant) to minimize the solution length.
* **Key Tasks:**
    * **State Space Search:** Navigating the massive state space (over 43 quintillion possibilities).
    * **Optimal Move Generation:** Calculating the minimum number of moves.

### 3. Mixed Reality Guidance (The Output Layer)
* **Purpose:** To overlay the solution path onto the physical cube in an intuitive, step-by-step manner.
* **Technology:** Augmented Reality (AR) or Mixed Reality (MR) framework (e.g., ARKit/ARCore, Unity/Unreal).
* **Key Tasks:**
    * **Pose Estimation:** Accurately tracking the cube's orientation in 3D space relative to the camera.
    * **Solution Overlay:** Projecting visual cues (arrows, highlighted facelets, animated turns) onto the physical object.
    * **User Feedback:** Detecting the user's successful completion of a move before advancing to the next step.

---

## 🔗 Connection to the Core Ecosystem

This project is a high-level demonstrator of integrated technologies from the user's wider portfolio:

* **Algorithmic Foundations:** The solver core relies heavily on the concepts of efficient search, data structures, and state space management defined in **`computhink-101`**.
* **Computer Vision Pipeline:** The CV component utilizes the robust data processing and image analysis techniques found in the **`data_sci-webdev`** methodology.
* **Immersive Interface:** The MR guidance system relies on the interface paradigms and frameworks explored within **`mobile_frameworks`**.
* **Pattern Recognition:** The ability to instantly map the colors and state is a powerful application of the pattern recognition research (similar to techniques in **`code-aesthetics`**).

## 🛠️ Technology Focus

* **Computer Vision (CV):** OpenCV, Python (NumPy, Scikit-image), Color Segmentation, Perspective Transformation.
* **Algorithms:** Kociemba's Two-Phase Algorithm, IDA\* Search, Breadth-First Search (BFS).
* **Mixed Reality (MR/AR):** ARKit/ARCore (native mobile) or Unity/C# for cross-platform MR.
* **Software Stack:** Python (for the Solver Core), Swift/Kotlin/Dart/C# (for the MR interface).
* **Optimization:** Focus on creating a lightweight solver core for fast execution on mobile devices.

---

## 🎯 Roadmap

* [ ] Implement a robust color segmentation algorithm for varying light conditions.
* [ ] Develop the core two-phase search algorithm to reliably find optimal solutions.
* [ ] Create the foundational AR interface for cube detection and tracking.
* [ ] Implement the solution overlay (arrows/highlighting).
* [ ] Add state validation logic (detect when the user correctly executes a turn).
* [ ] Optimize the entire pipeline for real-time mobile performance.
