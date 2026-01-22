# Quick Emergency Alert Button for Women Safety

## 📖 Project Overview
Personal safety emergencies require fast and reliable communication. In critical situations, using a smartphone may be difficult or impossible.  
This project implements a **Quick Emergency Alert Button** that sends an SOS message with real-time GPS location to pre-defined contacts using a **single button press**.

The project is implemented using **two independent approaches**:
1. IoT-based hardware prototype  
2. VLSI / ASIC-level digital design using open-source tools  

---

## 🎯 Objectives
- Enable **single-press emergency activation**
- Send **GPS coordinates via GSM SMS**
- Operate **independently of smartphones**
- Demonstrate scalability from **hardware prototype to ASIC design**

---

## 🧩 Project Architecture

### 1️⃣ IoT-Based Hardware Implementation
- Push button triggers the emergency sequence
- Microcontroller reads GPS coordinates
- SOS message is formatted and sent via GSM
- Designed for real-world emergency use

### 2️⃣ VLSI / ASIC Implementation
- Emergency controller modeled as a **Finite State Machine (FSM)**
- Implemented in **Verilog HDL**
- Verified through simulation and waveform analysis
- Converted to **ASIC-ready layout** using open-source EDA tools

---

## 🛠️ Tools & Technologies

### IoT / Embedded
- Arduino IDE
- Microcontroller (Arduino / ESP32)
- GPS Module (NEO-6M)
- GSM Module (SIM800 / SIM900)
- UART / Serial Communication

### VLSI / Digital Design
- Verilog HDL
- Icarus Verilog
- GTKWave
- Yosys
- OpenLane
- Sky130 PDK
- Magic
- KLayout

---

## 🧪 Verification & Testing
- Hardware testing for GPS acquisition and GSM SMS delivery
- RTL simulation using Icarus Verilog
- FSM and UART waveform verification using GTKWave
- DRC and LVS checks for ASIC layout

---

## 📌 Key Features
- One-press emergency alert
- GPS-based location tracking
- GSM SMS communication (no internet required)
- Low-power and scalable ASIC design

---

## 🚀 Future Scope
- Miniaturization into wearable devices
- Integration of low-power sleep modes
- Secure message transmission using encryption
- ASIC tape-out using MPW shuttle services

---

## 👩‍💻 Contributors
- Kriti Agrawal  
- Yogita Sharma  
- Nishu Tandon  

---

## 📜 License
This project is for academic and educational purposes.
