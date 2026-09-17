

Profile readme · MD
<div align="center">
# 👋 Hi, I'm Toluwanimi Alfred (@alfredoeinsteino2024)
 
**Mechatronics Engineering Student | C Programmer | Aspiring Firmware Engineer | Systems Builder**
 
[![GitHub](https://img.shields.io/badge/GitHub-alfredoeinsteino2024-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-toluwanimialfred-0A66C2?style=flat-square&logo=linkedin)](https://www.linkedin.com/in/toluwanimialfred/)
[![X](https://img.shields.io/badge/X-AlfredFadipe-000000?style=flat-square&logo=x)](https://x.com/AlfredFadipe)
[![HarvestIQ](https://img.shields.io/badge/HarvestIQ-Live%20Product-4CAF50?style=flat-square)](https://alfredoeinsteino2024.github.io/harvestiq)
 
</div>
---
 
## 🚀 About Me
 
- 🌾 Founder & sole builder of **HarvestIQ** — a live, deployed USSD agritech platform serving Nigerian smallholder farmers
- 🔧 Embedded Systems and C Programmer, aspiring **Game Engine Developer**
- 🎓 Mechatronics undergraduate focused on **IoT**, **embedded systems**, and **agentic software testing**
- ✈️ Building **AeroForge** — a browser-based aircraft aerodynamics simulator with a C physics engine compiled to WebAssembly
- 🚕 Built **FJAY Dispatch** — a USSD-based campus transport/dispatch system (final year project, built for a client — private repo)
- 🛡️ Building **AI-powered testing platforms** that validate IoT device management systems
- 💳 Building **confidential payment systems** using C and embedded hardware
- 🖥️ Developing **SDL2 applications**, system-level projects, and hardware integrations
- ⚡ Working with **microcontrollers**, real-time systems, and decentralized payment concepts
- 🤖 Using **Claude Code** as my primary AI-assisted development tool across all projects
- 📈 Continuously building and improving through hands-on engineering work
---
 
## 🛰️ Latest Project: ESP32 Radar Scanner
 
> **A Search-and-Track Ultrasonic Radar System, Modeled on Real Fire-Control Radar Behavior**
 
A tracking radar built on an ESP32 that behaves like the real thing: it searches at full sweep speed, locks onto anything in range, dwells to confirm and track it, then deliberately resumes the sweep — engineered so a static decoy can never pin it on one bearing while something else moves through an unwatched angle.
 
- 🔄 Continuous 0°–180° servo sweep with real-time angular zone classification (A–D)
- 🎯 Automatic search → track → resume state machine, modeled on fire-control radar dwell behavior
- 🔊 Distance-proportional buzzer escalation — beep rate accelerates as objects close in
- 🛡️ Anti-decoy design — the sweep always completes its pass, so it can't be permanently pinned on one bearing
- 📡 Live WiFi telemetry via HTTP POST, JSON payloads, to a Node backend
- 🖥️ Real-time web dashboard visualizing scan data as it streams in
**Tech Stack:** C++ (Arduino/ESP32) · ESP32Servo · ArduinoJson · HC-SR04 · SG90 Servo · Node.js · HTML/CSS/JS
 
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/esp32-radar-scanner)
 
---
 
## 🌾 Featured Project: HarvestIQ
 
> **Postharvest Intelligence for Nigerian Smallholder Farmers — Live on AWS**
 
Nigerian farmers lose **40% of their harvest** worth **₦5 trillion annually** — not from poor farming, but lack of information in the 72 hours after harvest. HarvestIQ solves this through USSD. No smartphone. No internet. Any phone, any network.
 
- 📱 **USSD platform** — farmers dial `*384*14367#` on any GSM phone to access market intelligence
- 💰 **Real-time prices** — live commodity prices from 6 major Nigerian markets (Kano, Lagos, Onitsha, Ibadan, Kaduna, Makurdi)
- 🤖 **AI storage advisory** — AWS Bedrock (Claude Haiku) generates crop-specific storage guidance
- 📦 **Produce listing** — farmers list in Nigerian units (bags, crates, tubers, bunches, baskets)
- 🔔 **SMS price alerts** — farmers set a floor price and get notified the moment the market reaches it
- 🏪 **Buyer dashboard** — live web portal for traders to browse listings and post demand requests
- 📲 **SMS price pipeline** — whitelisted market agents submit daily prices via SMS keyword commands
- ☁️ **Fully serverless** — AWS Lambda, DynamoDB, API Gateway, SNS, EventBridge, Bedrock — all deployed
- ✅ **15/15 unit tests passing**
**Tech Stack:** Node.js · AWS Lambda · DynamoDB · API Gateway · AWS Bedrock · SNS · EventBridge · Africa's Talking · AWS SAM · GitHub Pages
 
[![Website](https://img.shields.io/badge/Website-Live-4CAF50?style=flat-square)](https://alfredoeinsteino2024.github.io/harvestiq)
[![Dashboard](https://img.shields.io/badge/Buyer%20Dashboard-Live-2D6A2D?style=flat-square)](https://alfredoeinsteino2024.github.io/harvestiq/buyer-dashboard.html)
[![Demo](https://img.shields.io/badge/Demo%20Video-Loom-625DF5?style=flat-square&logo=loom)](https://www.loom.com/share/80ed99dd5a3d4274bf682c34fc8fcbaa)
[![Repo](https://img.shields.io/badge/Backend-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/harvestiq-backend)
 
> Submitted to **Startup Abuja Innovation Challenge 2026** and **OPay National Innovation Challenge 2026** (Team AgroMinds, FUT Minna)
 
---
 
## 🚨 Previous Project: RescueHacks Alert
 
> **Built for RescueHacks 2026 — Discreet USSD Emergency Alert System**
 
A USSD code that looks exactly like checking an airtime balance — but silently triggers a real-time emergency alert the moment it's dialed. No menu, no confirmation screen, no visible evidence on the phone.
 
- 📵 **No interactive menu** — emergency type is encoded directly in the dialed digits, so the response is instant with no screens shown
- 🕶️ **Deliberately neutral response** — every dial returns an identical, boring cover message, whether or not an alert was triggered
- 💬 **Silent WhatsApp alert** — sends emergency type, caller's number, and timestamp to a trusted contact via Meta's WhatsApp Cloud API
- ☁️ **Serverless on AWS** — Lambda, API Gateway, SSM Parameter Store, deployed via AWS SAM
- 📡 **Africa's Talking USSD gateway** for the discreet dial-code trigger
- 🔭 **Long-term vision:** routing alerts to registered security operatives, with telecom partnership for lawful location assistance
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/rescuehacks-alert)
 
---
 
## ✈️ Project: AeroForge
 
> **Browser-based Aircraft Aerodynamics Simulator**
 
A real-time wing aerodynamics simulator running entirely in the browser, powered by a C physics engine compiled to WebAssembly. Students can design any wing shape and instantly see the aerodynamic consequences.
 
- ⚙️ **C physics engine** implementing the Vortex Lattice Method (VLM) with Biot-Savart horseshoe vortex computation
- 🔬 **Gaussian elimination solver** computing lift distribution across arbitrary wing geometries
- 🌐 **Compiled to WebAssembly** via Emscripten — near-native C performance running in the browser
- 🎮 **Three.js 3D visualization** with real-time pressure color mapping (red = high pressure, blue = low pressure)
- 💨 **Animated streamlines** showing airflow behavior over the wing surface
- ⚠️ **Stall warning system** — wing flashes red when angle of attack exceeds critical threshold
- 📊 **Live CL, CD, L/D ratio, pitch moment, and lift force** — all computed from real aerodynamic equations
- 🎛️ Parametric controls: wingspan, chord, taper, sweep angle, dihedral, angle of attack, airspeed
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/aeroforge)
 
---
 
## 🛡️ Previous Project: SensorSentinel
 
> **Built for UiPath AgentHack 2026 · Track 3: Agentic Software Testing with UiPath Test Cloud**
 
An AI-powered agentic testing platform that validates IoT device management systems using three specialized test agents orchestrated through UiPath Test Cloud.
 
- 🔬 **C-based IoT device simulator** generating realistic and anomalous sensor data (temp/humidity/voltage) with XOR-shift RNG and chaos injection mode
- 🌐 **Python Flask REST API** with thread-safe deque store, severity classification, and real-time anomaly detection across 5 anomaly types
- 📊 **Live web dashboard** with Chart.js visualizations and real-time anomaly feed
- 🤖 **3 specialized AI test agents** — API Agent (36 tests), UI Agent (27 tests), Anomaly Detection Agent (32 tests)
- ✅ **95/95 test cases passing** across API correctness, UI behavior, and anomaly detection accuracy
- 🔁 **UiPath Test Cloud** as the orchestration and governance layer tying all agents together
- 🧠 Built end-to-end with **Claude Code** — architecture, C simulator, Flask API, dashboard, and all 95 test cases
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/SensorSentinel)
 
---
 
## 🔗 Previous Project: ChainEngineers Midnight
 
> **Built for MLH Midnight Hackathon 2026 · DeFi Track**
 
A privacy-focused embedded payment terminal designed for small merchants in Nigeria. Built as a digital twin simulator in C with SDL2, connected to a Node.js backend and the Midnight Network for confidential blockchain transactions using zero-knowledge proofs.
 
- 🖥️ Terminal UI in **C and SDL2** with state machine architecture and **8 screen flows**
- 🔌 Raw **Winsock2 TCP socket** communication without external networking libraries
- 🔒 **Zero-knowledge commitment scheme** — transaction details remain private
- 📱 Real-time **QR code generation** for Midnight payment URIs
- 📜 Compact **smart contract logic** implementing payment circuits
- 🧵 Multithreaded system using **SDL threads and mutex synchronization**
- 💱 Currency conversion between **Nigerian Naira and DUST token**
[![Demo](https://img.shields.io/badge/Demo-Facebook-1877F2?style=flat-square&logo=facebook)](https://www.facebook.com/share/v/1BV5oQZhwY/)
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/chainengineers-midnight)
 
---
 
## ⚡ Previous Project: ChainEngineers Solana
 
> **Built for Dev3Pack Global Hackathon 2026 · Solana Track**
 
An embedded payment terminal prototype for emerging market merchants, built as a digital twin in C with SDL2 and integrated with Solana Devnet.
 
- 🖥️ Terminal UI in **C and SDL2** using state machine design with **6 screens**
- 🔌 Raw **Winsock2 TCP socket** communication without external libraries
- 📱 Real-time **Solana Pay QR code generation**
- ✅ Live **transaction confirmation** on Solana Devnet
- 🧵 Multithreaded architecture using **SDL threading and mutexes**
[![Demo](https://img.shields.io/badge/Demo-Loom-625DF5?style=flat-square&logo=loom)](https://www.loom.com/share/e6a757cfbf9748fab841fae9ae3bcf45)
[![Repo](https://img.shields.io/badge/Repo-GitHub-181717?style=flat-square&logo=github)](https://github.com/alfredoeinsteino2024/chainengineers)
 
---
 
## 🛠️ Tech Stack
 
### Languages
![C](https://img.shields.io/badge/C-00599C?style=flat-square&logo=c&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat-square&logo=nodedotjs&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
 
### Cloud & Serverless
![AWS Lambda](https://img.shields.io/badge/AWS%20Lambda-FF9900?style=flat-square&logo=awslambda&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)
![AWS Bedrock](https://img.shields.io/badge/AWS%20Bedrock-FF9900?style=flat-square&logo=amazon&logoColor=white)
![API Gateway](https://img.shields.io/badge/API%20Gateway-FF4F8B?style=flat-square&logo=amazon&logoColor=white)
![AWS SAM](https://img.shields.io/badge/AWS%20SAM-FF9900?style=flat-square&logo=amazon&logoColor=white)
![SNS](https://img.shields.io/badge/AWS%20SNS-FF9900?style=flat-square&logo=amazon&logoColor=white)
 
### USSD & Telecom
![Africa's Talking](https://img.shields.io/badge/Africa's%20Talking-F5A623?style=flat-square)
![USSD](https://img.shields.io/badge/USSD-2D6A2D?style=flat-square)
![SMS](https://img.shields.io/badge/SMS%20Gateway-4CAF50?style=flat-square)
 
### Systems & Graphics
![SDL2](https://img.shields.io/badge/SDL2-1C2C3E?style=flat-square)
![Winsock2](https://img.shields.io/badge/Winsock2-0078D4?style=flat-square&logo=windows&logoColor=white)
![WebAssembly](https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white)
![Emscripten](https://img.shields.io/badge/Emscripten-000000?style=flat-square)
![Multithreading](https://img.shields.io/badge/Multithreaded%20Programming-555555?style=flat-square)
 
### Frontend & 3D
![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=threedotjs&logoColor=white)
![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)
 
### Backend & Testing
![Flask](https://img.shields.io/badge/Flask-000000?style=flat-square&logo=flask&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat-square&logo=express&logoColor=white)
![Jest](https://img.shields.io/badge/Jest-C21325?style=flat-square&logo=jest&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-0A9EDC?style=flat-square&logo=pytest&logoColor=white)
![Selenium](https://img.shields.io/badge/Selenium-43B02A?style=flat-square&logo=selenium&logoColor=white)
 
### Hardware
![Arduino](https://img.shields.io/badge/Arduino-00878F?style=flat-square&logo=arduino&logoColor=white)
![ESP32](https://img.shields.io/badge/ESP32-E7352C?style=flat-square)
![ESP8266](https://img.shields.io/badge/ESP8266-E7352C?style=flat-square)
![HC-SR04](https://img.shields.io/badge/HC--SR04%20Ultrasonic%20Sensor-007ACC?style=flat-square)
![MAX30105](https://img.shields.io/badge/MAX30105%20Heart%20Rate%20Sensor-FF4444?style=flat-square)
![DS18B20](https://img.shields.io/badge/DS18B20%20Temp%20Sensor-FF8800?style=flat-square)
 
### Agentic Testing & Orchestration
![UiPath](https://img.shields.io/badge/UiPath%20Test%20Cloud-FA4616?style=flat-square&logo=uipath&logoColor=white)
![Claude Code](https://img.shields.io/badge/Claude%20Code-D97757?style=flat-square)
 
### Blockchain
![Midnight Network](https://img.shields.io/badge/Midnight%20Network-0D0D0D?style=flat-square)
![Solana](https://img.shields.io/badge/Solana-9945FF?style=flat-square&logo=solana&logoColor=white)
![Solana Pay](https://img.shields.io/badge/Solana%20Pay-9945FF?style=flat-square&logo=solana&logoColor=white)
 
---
 
## 🎯 Current Projects
 
| Project | Description | Stack | Status |
|---|---|---|---|
| **ESP32 Radar Scanner** | Search-and-track ultrasonic radar with anti-decoy dwell logic and a live dashboard | C++, ESP32, Node.js | ✅ Complete |
| **HarvestIQ** | USSD postharvest intelligence platform for Nigerian farmers | Node.js, AWS, Africa's Talking | ✅ Live & Deployed |
| **RescueHacks Alert** | Discreet USSD emergency alert system | AWS Lambda, Africa's Talking, WhatsApp Cloud API | ✅ Complete |
| **AeroForge** | Browser-based aircraft aerodynamics simulator with C+WASM physics engine | C, WebAssembly, Three.js | 🚧 In Progress |
| **FJAY Dispatch** | USSD-based campus transport/dispatch system (client project) | Node.js, AWS, Africa's Talking | ✅ Complete — Private Repo |
| **SensorSentinel** | AI-powered agentic testing platform for IoT device management | C, Python, Flask, UiPath | ✅ Complete |
| **ChainEngineers Midnight** | Confidential embedded payment terminal on Midnight Network | C, SDL2, ZK Proofs | ✅ Complete |
| **ChainEngineers** | Solana-based embedded payment terminal | C, SDL2, Solana | ✅ Complete |
| **14 C Project Challenge** | Mastering C and systems programming through project-based learning | C | 🚧 In Progress |
 
---
 
## 📊 GitHub Stats
 
<div align="center">
![GitHub Stats](https://github-readme-stats.vercel.app/api?username=alfredoeinsteino2024&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117)
 
![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=alfredoeinsteino2024&layout=compact&theme=dark&hide_border=true&bg_color=0d1117)
 
</div>
---
 
## 📫 Contact
 
- 🐙 **GitHub:** [github.com/alfredoeinsteino2024](https://github.com/alfredoeinsteino2024)
- 💼 **LinkedIn:** [linkedin.com/in/toluwanimialfred](https://www.linkedin.com/in/toluwanimialfred/)
- 🐦 **X:** [x.com/AlfredFadipe](https://x.com/AlfredFadipe)
- 🌾 **HarvestIQ:** [alfredoeinsteino2024.github.io/harvestiq](https://alfredoeinsteino2024.github.io/harvestiq)
- 📧 **Email:** harvestiqng@gmail.com
---
 
<div align="center">
*"Learning by doing — through continuous system building."*
 
</div>
 
