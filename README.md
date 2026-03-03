# Cost-Effective Overhead AC Conductor Breakage Detection System

A low-cost IoT based system designed to detect breakage faults in low voltage overhead distribution lines and provide real-time alerts through a web dashboard.

This project aims to improve public safety and reduce response time for electrical faults in power distribution networks.

---

## Smart India Hackathon Problem Statement

This project is developed based on a problem statement from **Smart India Hackathon (SIH)**.

The challenge focuses on creating an affordable and scalable solution for detecting breakage faults in low-voltage overhead distribution conductors and preventing electrical accidents.

The system provides:

- Real-time conductor fault detection
- Instant alerts to substations
- Public safety notifications
- Dashboard monitoring system

---

## Problem Statement

Broken overhead distribution conductors can cause serious accidents because electricity may still flow through the wire even after it falls to the ground.

Current safety devices such as fuses often fail to detect such faults.

Major causes of conductor breakage include:

- Storms and strong winds
- Falling trees
- Aging infrastructure
- Corrosion or rust

This project proposes a **cost-effective and scalable monitoring system** that detects conductor breakage and immediately alerts authorities and the public.

---

## Project Objectives

- Detect breakage faults in overhead distribution lines
- Automatically send alerts to electricity authorities
- Provide a dashboard for monitoring faults
- Alert nearby residents to avoid danger
- Provide a low-cost alternative to expensive SCADA systems

---

## System Architecture

The system uses IoT sensors installed on distribution poles.

Components include:

- ESP32 Microcontroller
- Current Sensors (CT)
- Voltage Sensors
- GSM / WiFi Communication Modules
- Relay Module
- Buzzer for local safety alerts
- Cloud dashboard for monitoring

Fault detection data is transmitted to a cloud server where it is processed and displayed on a web dashboard.

---

## Technologies Used

### Hardware
- ESP32 Microcontroller
- Current Transformer Sensors
- Voltage Sensors
- GSM Module (SIM800/900)
- Relay Module
- Buzzer

### Software
- ESP-IDF for ESP32 programming
- Python for cloud data processing
- AWS IoT for cloud connectivity
- Web Dashboard (HTML, CSS, JavaScript)

---

## Features

- Real-time fault detection
- Instant alerts to substations
- SMS alerts to nearby residents
- Dashboard monitoring system
- Local buzzer alert for public safety
- Scalable deployment (Street → Village → Grid)

---

## Dashboard Functions

The Distribution Fault Dashboard allows operators to:

- Monitor faults in real time
- Identify fault locations
- Notify residents within **500 m – 5 km radius**
- Send safety advisories through SMS alerts

---

## Cost Analysis

Traditional SCADA or smart grid systems:

- Cost: ₹10–20 Lakhs
- Implementation time: 12–18 months

Our proposed solution:

- Cost: ₹40,000 – ₹60,000
- Implementation time: 3–4 months

This makes the system approximately **95% cheaper** than conventional solutions.

---

## Project Motto

"Smart, selective, and low-cost real-time fault detection for uninterrupted electricity supply."

---

## Team Members

- N. Jayaram Satya Santosh – EEE (2nd Year)
- Ch. Durga Sai Varshini – EEE (2nd Year)

---

## Project Theme

Disaster Management

---

## License

This project is developed for academic and research purposes.
