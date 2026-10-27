# Medical-Grade-OT-Light-Controller
Production-ready medical OT light controller with advanced noise isolation.
# Medical-Grade Operating Theatre (OT) Light Controller

A high-reliability, custom-engineered control system for medical Operating Theatre (OT) luminaires. Developed to replace and optimize legacy lighting systems with robust noise isolation, precision PWM dimming, and medical-grade operational stability.

## 📌 Project Overview
* **Application:** Hospital Surgical Suites / OT Lights
* **Production Volume:** 75+ units fabricated via JLCPCB and successfully field-deployed.
* **Core Engineering:** Reverse engineering, multi-board noise decoupling, analog/digital control, and thermal-aware PCB layout.

---

## ⚙️ Key Technical Features

* **3-Board Segregated Architecture:** Logic, power switching, and power supply are split across isolated physical layouts to prevent high-frequency switching interference from reaching sensitive control circuits.
* **Flicker-Free Brightness Modulation:** High-frequency PWM implementation ensures uniform illumination without visible flicker, meeting medical-grade surgical lighting standards.
* **Safety & Reliability:** Integrated thermal cutoffs, overcurrent protection, and input transient suppression.
* **Production Engineering:** Generated full DFM (Design for Manufacturing) packages and managed batch assembly runs.

---

## 📁 Repository Structure

* `Hardware/` - High-level functional schematics, block diagrams, and hardware architecture documentation. *(Proprietary design files withheld)*
* `Firmware/` - Driver abstraction routines, timing loops, and hardware control logic snippets.
* `Media/` - Production run boards, surface-mount assembly, and hardware verification images.

---

## 🛠️ Tools & Technologies Used
* **EDA / Simulation:** Proteus Design Suite
* **Manufacturing:** JLCPCB (Multi-layer fabrication, lead-free HASL)
* **Testing Equipment:** Oscilloscope, Digital Multimeter, Regulated DC Bench Supply

---

*Note: Proprietary production schematics and full firmware source code are proprietary assets and are available under NDA upon verified client engagement.*
