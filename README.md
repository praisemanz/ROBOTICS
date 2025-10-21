# ROBOTICS
Robot Version 1: https://instructions.online/?id=4063-2025-2026_v5rc_hero_bot_dex
Robot Version 2: https://instructions.online/?id=4094-2024%202025%20vrc%20hero%20bot 

# 🤖 VEX Robotics 2024–2025 Hero Bot: **Axel**

Welcome to the official documentation and codebase for **Axel**, the 2024–2025 **VEX V5 Hero Bot** built for the **VEX Robotics Competition (VRC) game: _High Stakes_**.

Axel is the educational reference robot designed by VEX to help new teams explore key mechanical and programming principles for this year’s game.  
This repository includes build notes and mechanical insights into Axel’s design.

---

## 🏆 Project Overview

**Competition Game:** VEX V5RC – *High Stakes* (2024–2025)  
**Robot Name:** Axel (Hero Bot)  
**Group Members:** Praise Manzi, Ehitnesh Tadese, Sabrine Shami Karanganwa
**Primary Function:** Collect rings on stakes; move mobile goals into scoring zones.  

---


## 🧰 Tools & Technologies Used

| Category | Tools/Components |
|-----------|------------------|
| **Hardware** | VEX V5 Smart Motors, V5 Brain, V5 Controller, V5 Battery, Vision Sensor (optional), Limit Switches |
| **Build System** | VEX V5 Structural Metal Kit, Shafts, Bearings, 4-Bar Linkage System, Intake Claw Assembly, Omni-Wheels |
| **Programming** | [VEXcode V5 (C++)](https://www.vexrobotics.com/vexcode-v5) |
| **Version Control** | GitHub for managing code and documentation |
| **Design Resources** | [VEX CAD Files](https://content.vexrobotics.com/cad), [Official Build Instructions](https://instructions.online/?id=4094-2024%202025%20vrc%20hero%20bot) |

---

## ⚙️ Mechanical Design

### 1. **Drivetrain**
- **Type:** 4-wheel tank drive using omni-wheels for agility.  
- **Motors:** 4 V5 Smart Motors (2 per side).  
- **Purpose:** High maneuverability for navigating between stakes and goals.  
- **Gear Ratio:** Standard 1:1 for consistent torque and speed balance.

### 2. **Lift Mechanism**
- **Type:** 4-bar linkage (parallel arm lift).  
- **Function:** Raises and lowers the intake assembly while maintaining horizontal alignment.  
- **Motor:** 1 Smart Motor with gear reduction for stability.  
- **Range of Motion:** Ground pickup → mid-stake height.

### 3. **Ring Intake**
- **Type:** Passive slope with guiding rails.  
- **Mechanism:** Gravity-assisted ring pickup as the robot drives forward.  
- **Add-on Option:** Roller intake for faster ring collection (custom modification).

### 4. **Scoring / Pusher System**
- **Type:** Motor-driven pusher plate.  
- **Purpose:** Pushes or releases rings onto stakes accurately.  

### 5. **Goal Mover (Attachment)**
- **Type:** Front-mounted fork or pusher bar.  
- **Function:** Push or drag mobile goals to scoring zones.  
- **Optional Automation:** Vision-assisted targeting (if sensor attached).

---
