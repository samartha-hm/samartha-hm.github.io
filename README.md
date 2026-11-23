# Samartha H M — Electronics Engineer & IoT Product Developer 🚀⚡

[![Portfolio Live](https://img.shields.io/badge/Live_Portfolio-samartha--hm.github.io-c87941?style=for-the-badge&logo=googlechrome&logoColor=white)](https://samartha-hm.github.io/)
[![License: MIT](https://img.shields.io/badge/License-MIT-444440?style=for-the-badge&logo=opensourceinitiative&logoColor=white)](LICENSE)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-samarthahm-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/samarthahm)
[![GitHub](https://img.shields.io/badge/GitHub-samartha--hm-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/samartha-hm)

> **Electronics & Communication Engineering graduate and IoT product developer** experienced in embedded firmware, PCB design, 4G/cloud connectivity, and robotics. Applies LLMs and AI coding agents to engineering research, rapid prototyping, and firmware debugging.

*Live Portfolio: [https://samartha-hm.github.io](https://samartha-hm.github.io/) | Official Resume: [`Samartha_HM_Resume.pdf`](Samartha_HM_Resume.pdf)*

---

## 👨‍💻 About Me

- **Education:** B.E. in Electronics & Communication Engineering — **Srinivas Institute of Technology, Valachil, Mangaluru** (VTU affiliated, CGPA: **7.79 / 10**, Graduated Jun 2026).
- **Core Engineering Competencies:**
  - **Embedded Firmware & Protocols:** Low-level C/C++ firmware, non-blocking finite state machines (IDLE/MANUAL/AUTO_TRAVERSE), PWM/GPIO control, and checksummed serial packet protocols (<50ms latency).
  - **PCB Layout & Circuit Validation:** KiCad/EasyEDA schematic capture, board routing, SMD/through-hole assembly, power electronics, sensor calibration, and oscilloscope/logic analyzer debugging.
  - **IoT & Cellular Telemetry:** 4G/LTE connectivity via SIM7670C modems, MQTT brokers, AWS EC2 cloud pipelines, and sensor multiplexing.
  - **Robotics & Vision:** Autonomous 5-motor 4WD platforms, vertical serpentine path planning, U-Net segmentation (Dice > 0.92), and ResNet-50 classification: 96.5% (unpeeled) and 98.2% (peeled).
  - **AI-Accelerated Development:** Deep workflow integration with Claude Code (CLI), Google Antigravity, local LLMs, and prompt engineering for rapid firmware prototyping and root-cause debugging.

---

## 🏆 Featured Engineering Projects

### 1. [Autonomous Smart Bot for Efficient Sun Drying of Arecanut (ARECAbot)](https://github.com/samartha-hm/ARECAbot) — *Capstone Project (4-Member Team)*
- **Problem:** Labor-intensive manual raking and inconsistent sun-drying cause 15–25% post-harvest crop loss for arecanut farmers.
- **Hardware Architecture:** Co-developed a 5-motor 4WD prototype (four drive motors + dedicated stirring roller) controlled via three BTS7960 motor drivers (40A peak load).
- **Dual-Controller System:**
  - **Orchestration:** Raspberry Pi 5 hosting a local Wi-Fi AP, FastAPI backend, and React web HMI with Hold-to-Move safety deadman switch.
  - **Real-Time Control:** Arduino Mega running deterministic C++ non-blocking FSM for real-time PWM motor generation.
- **Protocol & Navigation:** Implemented vertical serpentine grid coverage and checksummed 6-byte UART packets achieving **<50ms command latency** with verified turning and boundary handling on field test grids.
- **Offline Vision Pipeline:** Evaluated a separate offline vision pipeline on 4,000 images using U-Net segmentation (Dice coefficient > 0.92) and ResNet-50 classification: **96.5% accuracy for four-stage grading of unpeeled nuts** and **98.2% for dry/not-dry classification of peeled nuts** (TensorFlow/Keras).

---

### 2. Experimind Labs — *Core Team Member (Feb 2026 – Present)*
*Promoted from Electronics Intern after 2 months.*
- Contribute across R&D, product engineering, and validation for education and IoT products; support execution, troubleshooting, and intern mentoring.
- **Educational IoT Kits:** Helped ship **100+ production units across two IoT kits, reaching 300+ students** with **98%+ first-pass assembly quality**; handled schematics, PCB layout, SMD/through-hole assembly, and debugging.
- **Water Quality Monitor v2.0 (R&D, Firmware & System Integration):**
  - Engineered 4G/LTE cellular telemetry using a SIM7670C modem and UART AT commands for an ESP32 multi-parameter monitor (pH, TDS, turbidity, temp, DO).
  - Built MQTT telemetry, FastAPI/WebSocket services, and live AWS EC2 dashboard.
  - **Resolved electrical probe crosstalk between pH and TDS sensors via GPIO-controlled sensor-phase multiplexing.**
- **GravityExplorer (Interactive School Science Exhibit — In Progress):**
  - Offline Windows interactive science exhibit with Electron and Three.js calculating visitor weights across 10 planets and moons.
  - Built sensor station with Arduino Uno, HX711 load cell, and arcade buttons.
  - Defined 115200-baud newline-delimited JSON serial protocol with sequence numbers, boot IDs, and acknowledgements; **implemented checksum-protected load-cell calibration storage in EEPROM**.
- **Land Survey Robot:** Developed Raspberry Pi Pico W firmware integrating GPS, magnetometer, and gyroscope data for navigation.

---

### 3. [AI-Powered Smart Waste Segregation](https://github.com/samartha-hm/ispark) — *ISPARK Learning Solutions*
- Built a smart waste-segregation prototype in 5 days using ESP32 sensor/servo control, ESP32-CAM, and a Python MobileNetV2 classifier (**79% accuracy on 600 images**) over UART.
- Achieved sub-second DRY/WET/SKIP sorting response with a custom serial protocol, confidence thresholding, and a real-time telemetry dashboard.

---

### 4. [Personal Tools & Automation Suite](https://github.com/simply1git) — *Independent Builds*
- **SyncPadIO:** Real-time peer-to-peer text & code sharing web application.
- **WebsiteON:** Serverless website uptime monitor with automated Telegram alerts.
- **SonicSync:** Low-latency WebRTC browser-to-browser audio broadcasting.
- **YotuDrive:** Multi-file YouTube storage engine with Reed-Solomon error-correction encoding.
- **Mobtola Pro:** Python ADB-based automated Android backup utility.

---

## 🎖️ Leadership & Extracurriculars

- **Event Organizer | ENVISION 2k25 National Tech Fest:** Organized the Line Follower robotics competition for 50+ participants and contributed to the promotional design team.
- **Editor & Designer | STEADY Department Club (2024 & 2025):** Designed the 50-page INCHARA magazine distributed to students and faculty; supported the planning and execution of technical and non-technical club events.
- **Junior Mentor | TECHBOTS Robotics Club:** Mentored juniors in embedded programming and PCB design; contributed to IoT and robotics systems development.
- **Content Creator | DreamBeatz YouTube:** Created music and lyrical-edit videos, applying video editing, graphic design, and audience-building skills; grew the channel to 3K+ subscribers.

---

## 🛠️ Technical Skills Matrix

| Domain | Technologies & Competencies |
| :--- | :--- |
| **Firmware** | Embedded C/C++, Python, non-blocking state machines, PWM/GPIO, checksum-based serial protocols |
| **Platforms & Interfaces** | Arduino UNO/Mega, ESP32/ESP32-CAM, Raspberry Pi 5/Pico W, Linux, UART/I2C/SPI, Wi-Fi, MQTT, 4G/LTE, GPS |
| **AI / Computer Vision** | TensorFlow/Keras, OpenCV, U-Net, ResNet-50, MobileNetV2, CNNs, transfer learning, image segmentation/classification |
| **Cloud & Web** | AWS EC2, FastAPI, REST APIs, WebSockets/Socket.IO, React, Node.js, TypeScript/JavaScript, SQLite |
| **Electronics & Validation** | KiCad, EasyEDA, LTspice, schematic/PCB design, SMD/through-hole assembly, multimeter, oscilloscope, logic analyzer, sensor calibration |
| **AI Development Workflows** | ChatGPT, Claude, Claude Code (CLI), Google Antigravity, local LLMs, Hugging Face and open-source model ecosystems, prompt engineering, AI-assisted coding/debugging |
| **Developer Tools** | Git/GitHub, VS Code, Jupyter Notebook, PowerShell |

---

## 📂 Repository Structure

```text
samartha-hm.github.io/
├── assets/
│   ├── areca-robot.jpg        # Capstone robot hero photo (view 1)
│   ├── areca-2.jpg            # Electronics & wiring view
│   ├── areca-3.jpg            # Chassis assembly & motor drives
│   ├── areca-4.jpg            # Field testing on drying yard
│   └── areca-5.jpg            # Mechanical roller & frame layout
├── index.html                 # Complete single-page portfolio application
├── Samartha_HM_Resume.pdf     # Official downloadable developer resume
├── LICENSE                    # MIT Open Source License
└── README.md                  # Comprehensive developer & project documentation
```

---

## 💻 Local Preview

To preview the portfolio locally:

```bash
# Clone the repository
git clone https://github.com/samartha-hm/samartha-hm.github.io.git

# Navigate to directory
cd samartha-hm.github.io

# Open index.html in your default browser
start index.html       # Windows
open index.html        # macOS
xdg-open index.html    # Linux
```

---

## 📬 Contact & Connect

- **Location:** Koppa, Chikkamagaluru, Karnataka, India
- **Email:** [samarth.h.m.gadikal@gmail.com](mailto:samarth.h.m.gadikal@gmail.com)
- **Phone:** +91 8073339032
- **LinkedIn:** [linkedin.com/in/samarthahm](https://linkedin.com/in/samarthahm)
- **GitHub:** [github.com/samartha-hm](https://github.com/samartha-hm)
- **Independent Builds:** [github.com/simply1git](https://github.com/simply1git)

---

## 📄 License

This repository is licensed under the [MIT License](LICENSE).
