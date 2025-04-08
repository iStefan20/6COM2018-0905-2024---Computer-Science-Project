UNIVERSITY OF HERTFORDSHIRE
Department of Computer Science



Modular BSc Honours in Computer Science



6COM2018-0905-2024 - Computer Science Project



Final Report
April 2025



A Security Perspective on the LoRaWAN Protocol: 
Analysis and Countermeasures against Cyberattacks

Stefan Ilie




Supervised by: W. Fernando


## 🧠 Project Overview

This project explores the security vulnerabilities within LoRaWAN, a widely used protocol for long-range, low-power IoT communication. The focus is on exposing and simulating critical attacks targeting LoRaWAN nodes, such as **replay attacks**, **jamming attacks**, and **battery depletion attacks**. The project combines theoretical research with both **visual Python simulations** and **practical Arduino experiments** to highlight how LoRaWAN’s architectural choices create potential weaknesses.


## 🎯 Project Objectives

- **Research Objective**  
  Review existing LoRaWAN architecture and security frameworks to identify vulnerabilities in communication, session management, and authentication.

- **Development Objective**  
  Simulate and practically demonstrate LoRaWAN attacks using Arduino MKR WAN 1310 boards, Python visualisation, and sensor data transmission.

- **Evaluation Objective**  
  Assess how these attacks affect LoRaWAN reliability, performance, and energy efficiency, and explore possible countermeasures.


## 🛠️ Technologies Used

- **Languages & Tools:** Python 3.12, Arduino IDE  
- **Libraries:** NumPy, Matplotlib, FuncAnimation  
- **Hardware:**  
  - 3x Arduino MKR WAN 1310  
  - 1x DHT22 Temperature Sensor  
  - 2x X000016 LoRa Antennas



### 3. **Simulations & Implementation**  
- **Python Simulations:**  
  - Visualised replay attacks (including frame counter checks)  
  - Animated jamming attacks (nodes unable to transmit under interference)  
  - Battery depletion effects through persistent fake packet activity

- **Arduino Practical Testing:**  
  - One board transmits temperature data  
  - A second board acts as an attacker (jammer or eavesdropper)  
  - A third board simulates a gateway receiving and displaying packets

