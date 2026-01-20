# Dual-MCU Opto-Isolated 8-Channel Wi-Fi Smart Controller

## 📌 Overview
This repository contains the **hardware design** of a smart controller PCB based on a
**dual-microcontroller architecture** using STM32 and ESP32.

The design focuses on **electrical safety, modularity, and noise immunity** by using
**optocoupler-based isolation** between control and communication sections.

The board provides **8 independent control channels**, making it suitable for
industrial and IoT control applications.

---

## ✨ Key Features
- Dual MCU architecture (STM32 + ESP32)
- Opto-isolated inter-MCU communication
- 8 independent output control channels
- Separate power and ground domains
- PCB designed with safety and EMI considerations

---

## 🧠 Uniqueness of the Design

### 🔹 Dual-MCU Architecture
- **STM32** handles real-time control, IO management, and safety logic
- **ESP32** handles Wi-Fi connectivity and future cloud or mobile app integration
- Separation improves system reliability and scalability

### 🔹 Opto-Isolated Communication
- MCU-to-MCU signals are isolated using optocouplers
- Protects low-voltage logic from noise and transients
- Prevents ground loop issues

### 🔹 8-Channel Modular Output
- 8 independent output channels
- Each channel can be interfaced with:
  - Relay modules
  - Solid-state switches
  - External driver circuits
- Suitable for multi-load control systems

### 🔹 Safety-Oriented PCB Design
- Isolated power domains
- Clear separation of control and communication sections
- Routing done to minimize noise coupling

---

## 🔧 Project Status
✔ Schematics completed  
✔ PCB designed  
✔ Gerber files generated  
✔ BOM prepared  
⏳ Firmware development planned  

---

## 🧠 Applications
- Industrial automation controllers
- Smart relay boards
- IoT-based switching systems
- Remote equipment control

---

## 🔜 Future Work
- STM32 firmware development
- ESP32 Wi-Fi firmware
- Communication protocol implementation
- Hardware testing and validation

---
<img width="1919" height="1079" alt="Screenshot 2026-01-20 223630" src="https://github.com/user-attachments/assets/79526072-afd4-493a-8ee7-271242131f56" />

<img width="1262" height="816" alt="Screenshot 2026-01-20 223805" src="https://github.com/user-attachments/assets/f76c97cc-0b71-4faa-a558-ab0da74ac6bd" />
<img width="1918" height="1079" alt="Screenshot 2026-01-21 004502" src="https://github.com/user-attachments/assets/ab129704-5201-43ff-9b96-b7027e0581c8" />
<img width="1919" height="1079" alt="Screenshot 2026-01-21 004537" src="https://github.com/user-attachments/assets/08b01404-5f8e-491f-8508-8fe6768f3a93" />
