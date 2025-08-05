# PMR Network Design – Wireless and Mobile Propagation Course

This repository contains the final project for the **Wireless and Mobile Propagation** course at Politecnico di Milano.  
The project focuses on designing and simulating a **Private Mobile Radio (PMR)** network for a 100 × 100 km area centered on Cedar City, Utah (USA).

## 📡 Project Overview
The designed PMR system is intended for professional users such as police, firefighters, and security services, providing reliable digital voice and data communication. The network uses a **SIMULCAST topology** with a VHF access layer and a microwave backbone for repeater interconnection.

## 🔹 Features
- **VHF User Access Network:**  
  - Frequency: 173 MHz  
  - Modulation: ETSI DMR (4-FSK)  
  - Repeaters: Motorola SLR5500  
  - Mobile units: Motorola DM4000e  
  - Omnidirectional antennas for wide-area coverage
- **Microwave Backbone Network:**  
  - Frequency: 10 GHz  
  - Radios: PTP 820S with 1.8 m parabolic antennas  
  - WR-90 waveguide for minimal signal loss  
  - Redundant mesh topology ensuring each repeater connects to at least two others

## 📊 Simulation & Planning
- Designed using **Radio Mobile** software
- Strategic repeater placement on mountain tops to maximize coverage
- Link budget calculations ensuring ≥10 dB safety margin above receiver sensitivity
- Full coverage maps and microwave link performance analysis

## 📈 Results
- 6 repeaters fully covering the 100 × 100 km region
- Reliable communication for all authorized users
- Robust microwave backbone with redundancy and weather resilience


