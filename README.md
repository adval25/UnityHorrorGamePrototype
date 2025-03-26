# Horror Game Prototype  

### Unity (C#) | Personal Project | 2024-2025

## 📌 Overview  
This is a third-person horror game prototype built in Unity, focusing on responsive gameplay and optimized graphical performace by importing models with baked lighting. The project leverages custom-built mechanics for movement and fixed cameras.

## 🎮 Features  

### 🔹 Character & Movement  
- **State Machine System** – Designed a modular state machine for character movement and animations.
- **Custom Character Controller** – Implemented precise movement using **raycasts** and velocity calculations, eliminating the overhead of rigidbody physics.  
- **Collision-Aware Camera System** – Developed a dynamic camera that adjusts based on environmental obstacles to maintain clear player visibility.  

### 🔹 AI & Combat  
- **AI-Driven Enemies** – Integrated **Unity’s NavMesh** for pathfinding, enabling enemies to navigate dynamically and transition smoothly between attacks and other behavior.  

### 🔹 Input & Interaction  
- **Unity’s Latest Input System** – Supports both keyboard and **controller input**.
- **Scalable Inventory System** – Designed a **list-based** inventory system that supports dynamic item additions while improving data retrieval speeds.  

### 🔹 Persistence & Optimization  
- **JSON-Based Save System** – Created a **serialization system** for storing position data (Vector3, Quaternion) and enemy attributes, ensuring persistent world states.  
- **Animation Retargeting & Optimization** – Improved animation blending using **animation layers** for seamless character animation transitions.  

## 🛠️ Technologies Used  
- Unity (C#)  
- Unity NavMesh  
- Unity Input System
- Unity Cinemachine
- JSON Serialization  
- Animation Layers & Retargeting
- Blender

## 🚀 How to Play  
1. Download and extract the build files.  
2. Run `HorrorGameDemo.exe`
3. After launching game, press 'M' on keyboard to display controls. Press alt-F4 to exit demo.

## 📜 Future Improvements  
- Implementing advanced enemy AI behaviors.  
- Expanding the weapon system with additional firearms and melee combat.  
- Refining the UI and HUD for an improved player experience.
- Keyboard controls.
