# 🚀 DockingSim.JS

**DockingSim.JS** is a high-fidelity, retro-vector orbital proximity operations simulator. Inspired by the **Universal Docking Display (UDD)** used during the historic **STS-114** Space Shuttle mission, this program is designed to preserve aerospace history and train the next generation of pilots in the delicate art of orbital docking.

---

## 📑 Table of Contents

* [Mission Purpose](#️-mission-purpose)
* [Simulation Features](#️-simulation-features)
* [Control Modes](#️-control-modes)
* [Pilot Controls](#️-pilot-controls)
* [Docking Requirements](#-docking-requirements)
* [Pro Pilot Tips](#-pro-pilot-tips)
* [Installation & Usage](#-installation--usage)
* [Safety Checklist](#-safety-checklist)

---

## 🛰️ Mission Purpose

The goal of this simulation is two-fold:

1. **Historical Preservation:** Recreate the aesthetic and functional feel of 2000s-era NASA flight software.
2. **Pilot Training:** Teach the physics of translation and velocity management required to dock with the International Space Station (ISS).

---

## 🛠️ Simulation Features

* **Vector Graphics Engine:** Low-latency green phosphor wireframe rendering.
* **Multi-View HUD:** Switch between internal FPV (First Person View) and external Side-Profile telemetry.
* **RCS Physics:** Realistic Reaction Control System (RCS) translation logic.
* **Dual-Input Support:** Seamlessly switch between Keyboard and Mouse-driven navigation.

---

## 🕹️ Control Modes

You can toggle between input methods using the **[T]** key.

1. **Keyboard Mode (Default):** Best for high-precision, incremental adjustments across all three axes.
2. **Mouse/Touch Mode:** Provides a more fluid "Joystick" feel for X and Y translation. Click and drag within the HUD to influence the ship's direction.

---

## ⌨️ Pilot Controls

### **System Commands**

| Key | Action |
| --- | --- |
| **[V]** | **Cycle View:** Switch between FPV and Side views |
| **[T]** | **Switch Input:** Toggle between Keyboard/Mouse control modes |
| **[SPACE]** | **RCS Null-Velocity:** Automated Braking Maneuver (Kills momentum) |

### **Movement (WASD + Arrows)**

| Function | Keyboard Input | Secondary Input |
| --- | --- | --- |
| **Y-Axis (Up/Down)** | **[W] / [S]** | **[Up Arrow] / [Down Arrow]** |
| **X-Axis (Left/Right)** | **[A] / [D]** | **[Left Arrow] / [Right Arrow]** |
| **Z-Axis (Forward/Back)** | **[Q] / [E]** | **[N/A]** |

> **Note on SIDE View:** In the side-profile camera, **W/S** controls Altitude (Y) and **A/D** controls your Approach/Z-axis distance.

---

## 📐 Docking Requirements

The locking mechanism will only engage if the following parameters are met at the moment of contact:

* **Velocity (VEL):** Must be **< 0.25 m/s**
* **Deviation (DEV):** Must be **< 0.60 m** (Center alignment)

---

## 💡 Pro Pilot Tips

> [!TIP]
> **Recommended Approach Protocol:**
> 1. **Initial Braking:** If your approach is too "hot," use **[SPACE]** to slow down and halt via the RCS Brake.
> 2. **Side-View Alignment:** Switch to **Side View** (**[V]**) first. Line up your altitude (Y) and distance (Z) relative to the docking port.
> 3. **FPV Centering:** Once the side profile looks good, switch to **FPV Mode**. Use the crosshairs and **WASD/Arrows** to align perfectly with the center of the port.
> 4. **Final Burn:** Carefully increase forward throttle (**[Q]**) until you reach an optimal, steady speed for the final docking procedure.

---

## 💾 Installation & Usage

Simply host the files on any static web server (like GitHub Pages).

1. **Clone the repository:**
```bash
git clone https://github.com/gamedev44/DockingSim.git
```

2. **Launch:** Open `index.html` in a modern web browser.
3. **Execute:** Initiate the Boot Sequence.

---

## 📋 Safety Checklist

<img width="2953" height="1796" alt="image" src="https://github.com/user-attachments/assets/095f219c-e2d7-4201-af8f-15d965c06852" />

---

**Author:** Asterisk

**Inspiration:** STS-114 UDD System

*Godspeed, Pilot.*
