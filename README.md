# BTech-Final-year-project-thesis

# IoT Enhanced Robotic Waste Collector with Blynk App Control and Metal Proximity Sensing

This repository contains the complete academic project report, system architecture blueprints, and source context for the B.Tech Capstone Thesis in Computer and Communication Engineering (CCE) at Amrita School of Engineering, Coimbatore.

## 📄 Project Document Link
* **Download Full Paper (PDF):** [ https://drive.google.com/drive/folders/1OKGeN98UTILSloyILY_DpAyrC2Z8vHZl?usp=drive_link ]

---

## 🔬 Abstract
Efficient metal waste collection and recycling are vital for reducing environmental risks in trash management. This project presents an autonomous on-site robotic waste management system utilizing an ESP32 microprocessor architecture for the automatic recognition, classification, and real-time segregation of metallic and non-metallic materials. 

Using localized inductive metal proximity sensors embedded within a modified dual-half dustbin manipulator, the system accurately detects target materials without physical component breakdown. The entire hardware framework is integrated into a live, collaborative software ecosystem via the Blynk Android application, facilitating real-time remote user control, edge data transmission over TCP/Wi-Fi topologies, and automated multi-threshold ultrasonic bin level monitoring.

---

## 🛠️ System Architecture & Engineering

The system bridges low-level hardware orchestration with scalable cloud infrastructure. It executes parallel computing tasks across a dual-core CPU processing layout to handle simultaneous sensor mapping and motor calibration routines.

### Core Hardware Components:
* **Central Processing Unit:** ESP32-WROOM-32 (With integrated Wi-Fi/Bluetooth dual-mode module)
* **Actuators & Control:** MG-996R and SG-90 Precision Servo Motors (180° rotational configuration) and High-Torque BO Motors
* **Sensors:** HC-SR04 Non-Contact Ultrasonic Sensors (Dual-row layout for real-time obstacle vs. trash identification) and an Inductive Metal Proximity Sensor
* **Power & Regulation:** 12V Lithium-Ion battery layout governed by IC7805 and IC7812 steady-state voltage regulators

### System Block Diagram Overview:
1. **Perception Layer:** Continuous environmental scanning via low-chassis ultrasonic arrays.
2. **Decision Layer:** Edge-algorithmic height threshold verification (Object Height < Chassis Height = Waste Identification).
3. **Manipulation Layer:** Sideways and vertical servo-driven grab sequences activating the non-contact inductive sensor.
4. **Segregation Layer:** Automated 180° bin rotation and selective sorting drop based on real-time binary logic data outputs.

---

## 📜 Authors & Academic Framework

* **Rangashree Dhanvanth R** (Roll No: CB.EN.U4CCE20048)
* **Aksshaya R**
* **Dorai Karthikeyan GM**
* **Swathi P**

* **Research Supervisor:** Dr. Ganesan M  
* **Department:** Electronics and Communication Engineering  
* **Institution:** Amrita School of Engineering, Coimbatore, Amrita Vishwa Vidyapeetham, India (B.Tech 2020-2024 Framework)

---

## 🏆 Publications & Status
* **Conference Context:** Peer-reviewed and accepted/submitted manuscript to the *2024 IEEE 4th Mysore Sub Section International Conference (MysuruCon)*.
* **Status:** Submitted.# IoT Enhanced Robotic Waste Collector with Blynk App Control and Metal Proximity Sensing

This repository contains the complete academic project report, system architecture blueprints, and source context for the B.Tech Capstone Thesis in Computer and Communication Engineering (CCE) at Amrita School of Engineering, Coimbatore.

## 📄 Project Document Link
* **Download Full Paper (PDF):** [ https://drive.google.com/drive/folders/1OKGeN98UTILSloyILY_DpAyrC2Z8vHZl?usp=drive_link ]

---

## 🔬 Abstract
Efficient metal waste collection and recycling are vital for reducing environmental risks in trash management. This project presents an autonomous on-site robotic waste management system utilizing an ESP32 microprocessor architecture for the automatic recognition, classification, and real-time segregation of metallic and non-metallic materials. 

Using localized inductive metal proximity sensors embedded within a modified dual-half dustbin manipulator, the system accurately detects target materials without physical component breakdown. The entire hardware framework is integrated into a live, collaborative software ecosystem via the Blynk Android application, facilitating real-time remote user control, edge data transmission over TCP/Wi-Fi topologies, and automated multi-threshold ultrasonic bin level monitoring.

---

## 🛠️ System Architecture & Engineering

The system bridges low-level hardware orchestration with scalable cloud infrastructure. It executes parallel computing tasks across a dual-core CPU processing layout to handle simultaneous sensor mapping and motor calibration routines.

### Core Hardware Components:
* **Central Processing Unit:** ESP32-WROOM-32 (With integrated Wi-Fi/Bluetooth dual-mode module)
* **Actuators & Control:** MG-996R and SG-90 Precision Servo Motors (180° rotational configuration) and High-Torque BO Motors
* **Sensors:** HC-SR04 Non-Contact Ultrasonic Sensors (Dual-row layout for real-time obstacle vs. trash identification) and an Inductive Metal Proximity Sensor
* **Power & Regulation:** 12V Lithium-Ion battery layout governed by IC7805 and IC7812 steady-state voltage regulators

### System Block Diagram Overview:
1. **Perception Layer:** Continuous environmental scanning via low-chassis ultrasonic arrays.
2. **Decision Layer:** Edge-algorithmic height threshold verification (Object Height < Chassis Height = Waste Identification).
3. **Manipulation Layer:** Sideways and vertical servo-driven grab sequences activating the non-contact inductive sensor.
4. **Segregation Layer:** Automated 180° bin rotation and selective sorting drop based on real-time binary logic data outputs.

---

## 📜 Authors & Academic Framework

* **Rangashree Dhanvanth R** (Roll No: CB.EN.U4CCE20048)
* **Aksshaya R**
* **Dorai Karthikeyan GM**
* **Swathi P**

* **Research Supervisor:** Dr. Ganesan M  
* **Department:** Electronics and Communication Engineering  
* **Institution:** Amrita School of Engineering, Coimbatore, Amrita Vishwa Vidyapeetham, India (B.Tech 2020-2024 Framework)

---

## 🏆 Publications & Status
* **Conference Context:** Peer-reviewed and accepted/submitted manuscript to the *2024 IEEE 4th Mysore Sub Section International Conference (MysuruCon)*.
* **Status:** Submitted.
