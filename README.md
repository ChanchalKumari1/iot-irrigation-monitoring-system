#  IoT-Based Smart Irrigation Monitor (ESP32)

#  Overview
Smart IoT irrigation monitor automates watering using real-time soil data, improving crop yield and reducing water wastage efficiently.
This project is built using ESP32 and Soil Moisture Sensor Probes, enabling real-time monitoring and automated irrigation control through IoT communication.
<img width="600" height="500" alt="IMG_2770 (1)" src="https://github.com/user-attachments/assets/c15c1a91-9f84-4fa2-b218-7bc1805ca15a" />


> This project represents a custom-built smart irrigation solution, developed as part of practical work by an<a href="https://digitalmonk.biz/iot-development-company-in-india/"> IoT Development Company in India</a>.

---

##  Features
- Real-time soil moisture monitoring  
- MQTT-based wireless communication  
- Automated irrigation control  
- Low-cost and easy-to-build system  
- Scalable for large-scale farming  
- Reduces water wastage  

---

##  Hardware Components
- ESP32  
- Soil  Sensor Probe 

---

##  Software & Tools
- Arduino IDE  
- MQTT Protocol  

## Problem
In agriculture, improper irrigation is a major challenge. Farmers often depend on manual inspection to decide when to water crops. This leads to:
- Overwatering or underwatering  
- Water wastage  
- Reduced crop yield  

Traditional irrigation systems lack real-time monitoring and automation, making them inefficient.

---
<img width="500" height="700" alt="Image (76) (2)" src="https://github.com/user-attachments/assets/932a0b61-e68e-4b66-9669-255d67660642" />


##  Solution
This project introduces an IoT-based irrigation monitoring system that:
- Continuously monitors soil moisture  
- Sends real-time data using MQTT  
- Automates irrigation decisions  

---

##  How It Works
1. Soil moisture sensor is placed in the soil  
2. ESP32 reads analog data via GPIO34  
3. ESP32 connects to WiFi  
4. Data is sent to an MQTT broker  
5. Every 30 seconds, system publishes:
   - Moisture value  
   - Soil status (DRY / WET)  
6. Based on moisture:
   - Dry soil → ON signal  
   - Wet soil → OFF signal  
7. MQTT pump controller controls the water pump  

---

##  Architecture
- Sensor Layer → Soil Moisture Probe  
- Controller → ESP32  
- Communication → MQTT  
- Actuator → Water Pump  

---


##  Setup Instructions

### ESP32 Setup
1. Install Arduino IDE  
2. Add ESP32 board support  
3. Upload code to ESP32  

### MQTT Setup
1. Configure MQTT broker  
2. Update credentials in code  
3. Monitor data using MQTT client  

---

##  Applications
- Smart farming  
- Automated irrigation  
- Garden monitoring  
- Water conservation  

---

##  Future Improvements
- Cloud dashboard integration  
- Mobile app monitoring  
- Multiple sensor support  
- AI-based automation

  ## More Details
For complete project explanation, real-world implementation, and working details:
 https://digitalmonk.biz/irrigation-monitor/ 

---

## 📄 License
This project is open-source and available under the MIT License.
