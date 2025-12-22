# 🚗 Team NovaVision - BFMC 2026

Welcome to the official repository of **Team NovaVision** for the **Bosch Future Mobility Challenge 2025**. Our goal is to develop a robust Level 3 autonomous driving system for a 1:10 scale vehicle capable of navigating a smart city environment.

## 📂 Project Structure

This repository is organized as a monorepo containing all subsystems:

* **`vehicle/`**: Code running on the actual car hardware.
    * `Brain`: High-level decision making & Computer Vision (Python/Raspberry Pi).
    * `Embedded`: Low-level control & sensor fusion (C++/Nucleo).
* **`pc_side/`**: Tools running on the development laptop.
    * `Simulator`: Gazebo simulation environment with Digital Twin.
    * `Dashboard`: Remote control and telemetry interface.
* **`utils/`**: Shared libraries and helper scripts.

## 🛠️ Tech Stack

* **Middleware:** ROS 2 (Robot Operating System)
* **Languages:** Python
* **Simulation:** Gazebo
* **Hardware:** Raspberry Pi 5, STM32 Nucleo, Camera, IMU

---
*Developed by Team NovaVision for BFMC 2025.*
