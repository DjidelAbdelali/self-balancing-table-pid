# Self-Balancing 3D Table PID Control

<div align="center">

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Interactive-brightgreen?style=for-the-badge&logo=googlechrome&logoColor=white)](https://djidelabdelali.github.io/self-balancing-table-pid/)
[![Portfolio](https://img.shields.io/badge/Portfolio-DJIDEL%20Abdelali%20Rayan-blue?style=for-the-badge&logo=react&logoColor=white)](https://djidelabdelali.github.io/portfolio/)
[![GitHub Repo](https://img.shields.io/badge/GitHub-Repository-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/DjidelAbdelali/self-balancing-table-pid)

</div>

---

## 📌 Project Overview

Closed-loop stabilization system for a mobile 3D platform. Real-time PID regulation with interactive proportional, integral, and derivative gain adjustment and physical response visualization.

This project is an engineering module built by **DJIDEL Abdelali Rayan** (Systems & Automation Engineer, USTHB).

---

## 🏗️ System Architecture & Data Flow

```mermaid
graph TD
    Gyro["IMU Sensor / Platform Pose"] --> Error["Error Calculation: Target vs Current Angle"]
    Error --> PID["PID Controller (P, I, D Gains)"]
    PID --> Actuators["Servo Motor Actuators X & Y"]
    Actuators --> Platform["Physical / WebGL 3D Platform Pose"]
    Platform --> Gyro
```

---

## 🛠️ Key Technologies & Frameworks

- **PID Regulation**
- **Control Systems**
- **Three.js**
- **Sensors & Actuators**

---

## 🚀 Live Interactive Web Demo

No installation required! Test and interact with the full web simulation live in your browser:
🔗 **[Launch Interactive Web Demo](https://djidelabdelali.github.io/self-balancing-table-pid/)**

---

## 🔗 Connected Portfolio Ecosystem

- 🌐 **Main Portfolio**: [djidelabdelali.github.io/portfolio](https://djidelabdelali.github.io/portfolio/)
- 💻 **GitHub Profile**: [github.com/DjidelAbdelali](https://github.com/DjidelAbdelali)
- 💼 **LinkedIn Profile**: [DJIDEL Abdelali Rayan](https://linkedin.com/in/djidel-abdelali-rayan-814b25207)

---

<div align="center">
  <sub>Developed by DJIDEL Abdelali Rayan — Systems & Automation Engineering</sub>
</div>
