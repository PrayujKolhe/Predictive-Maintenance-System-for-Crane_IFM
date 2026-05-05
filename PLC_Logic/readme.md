# ⚙️ PLC Control Logic – IO-Link Smart Safety Monitoring System

This Project was developed and tested using CODESYS V3.5 SP18 Patch 0.

## 📌 Overview

This repository contains the **PLC programming logic** developed for an **IO-Link Based Smart Overload & Safety Monitoring System** using the **IFM CR710S PLC** and **CODESYS SP16**.

The PLC program performs:
- Real-time sensor monitoring
- Multi-level alarm handling
- Safety shutdown logic
- IO-Link diagnostics processing
- Modbus TCP communication
- HMI variable handling

---

## 🛠️ Technologies Used

- IFM CR710S PLC
- CODESYS SP16
- Structured Text (ST)
- Ladder Diagram (LD)
- Modbus TCP
- IO-Link Communication

---

## 📂 PLC Logic Features

### ✅ Real-Time Monitoring
- Vibration sensor monitoring
- Temperature sensor monitoring
- Continuous threshold evaluation

### ✅ Multi-Level Alarm Logic
- NORMAL
- WARNING
- CRITICAL SHUTDOWN

### ✅ Intelligent Safety Features
- 5-second delay timer
- Emergency shutdown logic
- Relay interlock control

### ✅ IO-Link Diagnostics
- Communication timeout detection
- Sensor fault detection
- Cable disconnection handling

### ✅ HMI Integration
- Alarm status variables
- Sensor value mapping
- System reset control
