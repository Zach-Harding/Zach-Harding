# Zach Harding

**Computer Engineer — embedded systems, computer vision, and the instrumentation in between.**

B.S. Computer Engineering @ Northwestern (McCormick) '26 · Minor in Economics · Managerial Analytics certificate from Kellogg · Seattle, WA

I build systems where silicon meets signal: flight recorders that survive power loss, vision pipelines that run on a Raspberry Pi, and the power boards underneath both.

[![LinkedIn](https://img.shields.io/badge/LinkedIn-zachharding34-0A66C2?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/zachharding34/)
[![Email](https://img.shields.io/badge/Email-zachharding34@gmail.com-EA4335?style=flat-square&logo=gmail&logoColor=white)](mailto:zachharding34@gmail.com)

---

## What I go deep on

| | |
|---|---|
| **Embedded Systems** | Firmware and instrumentation on real hardware — flight recorders logging transducer data on Linux, MCU peripherals driven directly over UART, SPI, I2C, PWM and ADC. |
| **Computer Vision & Image Processing** | Research-grade texture similarity (STSIM) benchmarked against neural models, feature-extraction pipelines robust to scale/rotation/lighting, CCL and morphology written from scratch. |
| **Data Systems & Telemetry** | Structured logging that survives power loss (SQLite + WAL), and the Flask and Grafana dashboards on top of it. |
| **Hardware & PCB Design** | Power-delivery boards in KiCad, debugged on the bench, rated through 28V transients under full flight-test load. |

---

## Featured projects

### 🦾 [Gesture-Controlled Robotic Arm](https://github.com/tahaazeem786/gesture_arm) &nbsp;`C++` `ESP32`
A wearable glove — IMU, flex sensors, push button — streams pose data to an ESP32 driving a LeArm servo arm, extending human dexterity and precision. Firmware, IMU integration layer, and a sensor test harness across 63 commits.

### ⚙️ [ME433 — Advanced Mechatronics](https://github.com/Zach-Harding/ME433) &nbsp;`C`
A full semester of embedded firmware: ADC/button/LED interfacing, display and sensor drivers, PWM motor control, I2C and SPI peripherals, and a final project. 17 assignments, 44 commits. The line-following buggy lives here.

### 🔬 STSIM Image Similarity Research — *Northwestern, Prof. Thrasyvoulos Pappas*
Benchmarking Structural Texture Similarity metrics against AI neural network models for computational imaging. Built feature-extraction pipelines over subband statistics (mean, variance, crossband correlation) to make similarity scoring invariant to scale, rotation and lighting — then ran K-means over a **23,000-image** botanical dataset to cluster species by similarity distance.

### ✈️ Embedded Flight Recording System — *AeroMech Inc.*
Real-time transducer capture on Linux in Python, logging structured telemetry through **SQLite with WAL** so nothing is lost to an abrupt shutdown. Paired with Flask GUIs and Grafana dashboards for low-latency diagnostics during flight test, plus OCR software that digitizes cockpit instrument values so test engineers stop transcribing by hand.

<details>
<summary><b>More engineering projects</b></summary>

<br>

- **Edge Computer Vision on Raspberry Pi** — Python CV model deployed at the edge, preprocessing live video streams to classify physical hardware profiles dynamically.
- **Line-Following Buggy** — PWM motor control with I2C and SPI sensor fusion, closing the loop with onboard image processing for real-time line tracking.
- **Connected Component Labeling & Morphology** — from-scratch image processing modules for boundary identification, object property analysis and automated size classification.
- **Claw Machine** — laser-cut and 3D-printed arcade claw driven by a Microbit: 4 motors, IR sensor and joystick over PWM and I2C.
- **Audio Filter & LED Spectrum Display** — analog filter chain lighting an LED array by input audio frequency.
- **Assembly Video Game** — sprite-based collision-avoidance game written in assembly.
- **Electromagnetic Box** — wired and programmed to self-deactivate on customizable cadences while powered.

</details>

---

## Toolbox

**Languages**

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![MATLAB](https://img.shields.io/badge/MATLAB-E16737?style=flat-square)
![R](https://img.shields.io/badge/R-276DC3?style=flat-square&logo=r&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/SystemVerilog-1A1A1A?style=flat-square)
![Assembly](https://img.shields.io/badge/Assembly-6E4C13?style=flat-square)

**Vision & ML**

![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat-square&logo=pandas&logoColor=white)

**Hardware**

![Arduino](https://img.shields.io/badge/Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square&logo=espressif&logoColor=white)
![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![LTSpice](https://img.shields.io/badge/LTSpice-0F4C81?style=flat-square)
![RISC-V](https://img.shields.io/badge/RISC--V-283272?style=flat-square&logo=riscv&logoColor=white)

**Systems & Tools**

![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white)
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Grafana](https://img.shields.io/badge/Grafana-F46800?style=flat-square&logo=grafana&logoColor=white)

---

## Experience

**Embedded Systems Intern** · AeroMech Inc., Seattle WA · *Summer 2024 & Summer 2025*
Flight recording systems, real-time telemetry visualization, 28V power-delivery PCB design, cockpit OCR.

**Undergraduate Researcher, Image Processing** · Northwestern University · *Apr 2025 – Jun 2026*
STSIM metrics, feature-extraction pipelines, large-scale image clustering.

**Web Developer** · Borrough Inc., Evanston IL · *Sep 2023 – Apr 2024*
Interactive UI/UX components and navigation systems that streamlined key user workflows.

---

<sub>Coursework: Computer Vision · Digital Signal Processing · Mechatronics · Microcontroller System Design · Feedback Systems · Circuits · Network Architecture · Computer Architecture · Data Analytics</sub>

<sub>Off the clock: baseball, fishing, hiking, skiing, and lifting.</sub>
