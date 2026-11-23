# Samartha H M — Embedded Systems & Robotics Engineer 🚀⚡

[![Portfolio Live](https://img.shields.io/badge/Live_Portfolio-samartha--hm.github.io-c87941?style=for-the-badge&logo=googlechrome&logoColor=white)](https://samartha-hm.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-444440?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-samarthahm-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samarthahm)
[![GitHub](https://img.shields.io/badge/GitHub-samartha--hm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/samartha-hm)

> **Welcome to the source repository for my personal engineering portfolio.**  
> I build complete embedded systems — from custom PCB design and circuit simulation through real-time firmware development to field-tested production deployment.

---

## 📸 Portfolio Preview

<p align="center">
  <a href="https://samartha-hm.github.io/">
    <img src="assets/webpage.png" alt="Samartha H M Portfolio Preview" width="100%" style="border-radius: 8px; border: 1px solid #c87941;" />
  </a>
</p>

*Live Site: [https://samartha-hm.github.io](https://samartha-hm.github.io/)*

---

## 👨‍💻 About Me

I am an **Electronics & Communication Engineering** graduate from **Srinivas Institute of Technology, Mangalore** (affiliated with Visvesvaraya Technological University - VTU, CGPA: **7.86 / 10**). 

My engineering focus spans the entire embedded product lifecycle:
- **PCB Design & Hardware Architecture:** Schematic capture, layout routing, SMD/through-hole fabrication, power isolation, and DFM (Design for Manufacturing).
- **Real-Time Firmware:** Low-level C/C++ firmware, non-blocking finite state machines (FSM), PWM generation, timer interrupts, and custom binary communication protocols.
- **Robotics & Sensor Fusion:** Multi-sensor integration (GPS, IMU, magnetometers, ultrasonic), differential drive kinematics, dead-reckoning serpentine path planning, and autonomous navigation.
- **Industrial Prototyping & Production:** Proven track record bringing designs from concept to 100+ production units with a **98%+ first-pass assembly quality yield**.

---

## 🏆 Key Engineering Highlights

### 1. [Autonomous Arecanut Drying Robot (ARECAbot)](https://github.com/samartha-hm/ARECAbot) — *Capstone Project (Team Lead)*
- **Problem:** Inconsistent manual sun-drying causes 15–25% post-harvest crop loss for arecanut farmers in rural India.
- **Architecture:** 4WD platform with a hierarchical 3-layer architecture:
  - **Frontend:** React/FastAPI/WebSocket dashboard with a **Hold-to-Move safety deadman switch** hosted via a local Raspberry Pi Wi-Fi access point (zero external internet dependency).
  - **Middleware:** Raspberry Pi 5 auto-detecting hardware ports, sensor telemetry logging, and supervisory control.
  - **Firmware:** Arduino Mega running a non-blocking FSM for deterministic real-time PWM motor generation.
- **Robust Protocol:** Designed a custom **6-byte binary XOR checksum protocol** between the controllers (<50ms latency) to discard corrupted packets.
- **Power Isolation:** Dual-battery architecture separating compute logic from 40A motor loads to prevent brownout resets.
- **Quality Assessment:** Validated an offline U-Net (Dice: 0.92) + ResNet-50 pipeline achieving **98.2% drying-stage classification accuracy**.

### 2. Experimind Labs — *Core Team Member & R&D Lead*
- Promoted from Electronics Intern to Core Team Member within 2 months.
- Engineered two educational hardware kits from concept through production:
  - **Kit 1:** 14-component sensor board (11 input sensors + 3 output actuators).
  - **Kit 2:** Multi-experiment robotics kit with IR/LDR sensing and motor driver circuitry.
- Supervised manufacturing run of **100+ production units delivered to 300+ students** with **98%+ first-pass quality**.
- Developed autonomous land survey robot firmware using **Raspberry Pi Pico W** with GPS + magnetometer + gyroscope sensor fusion.

### 3. [AI-Powered Smart Waste Segregation](https://github.com/samartha-hm/ispark) — *ISPARK Learning*
- Engineered an automated sorting prototype in 5 days using ESP32 + ESP32-CAM.
- Integrated Python MobileNetV2 computer vision classifier (**79% accuracy on 600-image dataset**) with custom serial protocol for sub-second sorting response.

### 4. [Cellular Water Quality Monitor](https://github.com/samartha-hm/Water-Quality-Monitor) — *R&D Field Telemetry*
- 4G/LTE cellular telemetry system utilizing **ESP32 + SIM7670C module + MQTT** to stream data directly to an AWS EC2 broker and WebSocket dashboard.
- Engineered interval-based sleep cycles for power-constrained rural deployments; tested continuously for 20+ hours with automatic reconnection upon signal drops.

---

## 🛠️ Technical Stack & Skills

| Domain | Technologies & Tools |
| :--- | :--- |
| **Embedded Platforms** | Arduino (Uno, Mega), Raspberry Pi 5, Raspberry Pi Pico W, ESP32, ESP32-CAM |
| **Firmware & Programming** | C / C++, Python, Embedded C, JavaScript, TypeScript, Bash |
| **Circuit Design & EDA** | KiCad, EasyEDA, LTspice, BTS7960 Motor Drivers, Power Electronics, SMD Soldering |
| **Robotics & Control** | Sensor Fusion (GPS, Magnetometer, Gyroscope, Ultrasonic), PWM Control, FSMs, Serpentine Grid Traversal |
| **IoT & Telemetry** | MQTT, SIM7670C (4G/LTE), WebSockets, AWS EC2, REST APIs, Serial/UART |
| **Computer Vision / AI** | MobileNetV2, OpenCV, U-Net Segmentation, ResNet-50 Classification |
| **Software & Developer Tools** | Git, Linux, VS Code, React, FastAPI, Node.js, WebRTC |
| **Creative & Media** | Adobe Premiere Pro, Canva, Graphic Design, Technical Publication |

---

## 📂 Repository Architecture

```text
samartha-hm.github.io/
├── assets/
│   ├── areca-robot.jpg        # Capstone robot hero photo (view 1)
│   ├── areca-2.jpg            # Electronics & wiring view
│   ├── areca-3.jpg            # Chassis assembly & motor drivers
│   ├── areca-4.jpg            # Field testing on drying yard
│   ├── areca-5.jpg            # Mechanical roller & frame layout
│   └── webpage.png            # OpenGraph and README preview image
├── index.html                 # Complete single-page portfolio application
├── Samartha_HM_Resume.pdf     # Official downloadable curriculum vitae
├── LICENSE                    # MIT Open Source License
└── README.md                  # Comprehensive developer & project documentation
```

---

## ⚡ Performance & Design Features

- **No Heavy Framework Overhead:** Handcrafted with semantic HTML5, pure CSS3, and lightweight vanilla ES6+ JavaScript.
- **Thematic Cyberpunk/Industrial UI:** Inspired by copper traces on raw circuit boards (`#c87941` copper accent on `#080808` dark substrate).
- **Animated SVG PCB Traces:** Dynamic circuit board traces and via pulse animations tailored to the hardware engineering identity.
- **Mobile First & Responsive:** Clean layout across mobile phones (320px+), tablets, and high-DPI desktop screens.
- **Touch & Gesture Enabled:** Interactive multi-photo project carousel with native touch swipe and keyboard navigation support.
- **SEO & Social Sharing Ready:** Full OpenGraph and Twitter Card metadata for rich previews on LinkedIn, Twitter, and messaging platforms.
- **Accessibility (WCAG AA):** High-contrast typography, semantic tags, accessible button controls, and touch-aware cursor behavior.

---

## 💻 Local Preview

To preview the portfolio locally, clone the repository and open `index.html` directly in your browser:

```bash
# Clone the repository
git clone https://github.com/samartha-hm/samartha-hm.github.io.git

# Navigate to the directory
cd samartha-hm.github.io

# Open index.html in default browser
# On Windows:
start index.html

# On macOS:
open index.html

# On Linux:
xdg-open index.html
```

Alternatively, serve it with any local static HTTP server:
```bash
npx serve .
# or
python -m http.server 8000
```

---

## 📬 Contact & Connect

- **Email:** [samarth.h.m.gadikal@gmail.com](mailto:samarth.h.m.gadikal@gmail.com)
- **Phone:** +91 8073339032
- **Location:** Koppa, Chikkamagaluru, Karnataka, India
- **LinkedIn:** [linkedin.com/in/samarthahm](https://linkedin.com/in/samarthahm)
- **GitHub:** [github.com/samartha-hm](https://github.com/samartha-hm)
- **Software Builds:** [github.com/simply1git](https://github.com/simply1git)

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
