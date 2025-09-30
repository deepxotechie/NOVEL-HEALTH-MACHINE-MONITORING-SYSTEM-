# NOVEL-HEALTH-MACHINE-MONITORING-SYSTEM-
Industrial machines face failures from vibration, noise, and overheating, causing downtime and high costs. Existing systems are costly and unfit for small industries. A low-cost solution uses ESP32 with accelerometer, sound, and temperature sensors, integrated with Raspberry Pi for real-time monitoring.
# Low-Cost IoT-Based Machine Health Monitoring System

# Overview
Industrial machines often face failures due to vibration, abnormal noise, and overheating, causing downtime and high maintenance costs. Existing monitoring systems are expensive and unsuitable for small industries. This project provides a low-cost solution using ESP32 with accelerometer, sound, and temperature sensors, integrated with a Raspberry Pi for real-time machine health monitoring.

# Features
- Vibration Monitoring: Detects abnormal vibrations via accelerometer  
- Noise Monitoring: Monitors unusual sounds using a sound sensor  
- Temperature Monitoring: Tracks machine overheating using ESP32’s in-built temperature sensor  
- Real-Time Dashboard: Raspberry Pi receives data and provides live monitoring and alerts  
- Low-Cost & Scalable: Affordable for small industries and easy to deploy  

# Hardware Components
ESP32 Microcontroller: Collects sensor data, preprocesses signals, and manages machine health monitoring.
Accelerometer: Detects vibrations, identifying imbalance, misalignment, and early machine faults.
Sound Sensor: Captures abnormal machine noises caused by wear, loose parts, or friction.
Temperature Sensor: Monitors overheating in machines to prevent thermal stress and damage.
Raspberry Pi: Enables Wi-Fi/Bluetooth communication and transmits health data to dashboards.
Cloud / Dashboard: Visualizes sensor data, provides alerts, and supports predictive maintenance decisions.

# Software Components
- Arduino IDE (for ESP32 programming)  
- Python (for Raspberry Pi dashboard and data processing)  
- Libraries: Adafruit_ADXL345, pyserial, matplotlib (for plotting)  
- Optional: Machine Learning models for predictive maintenance  

## System Architecture
[ESP32 Sensors] --> [ESP32 Microcontroller] --> [Wi-Fi/MQTT] --> [Raspberry Pi] --> [Dashboard/Alerts]
<img width="419" height="486" alt="image" src="https://github.com/user-attachments/assets/8a26f544-c33f-409f-b3b1-528b11a3ed4e" />


# How It Works
1. ESP32 collects vibration, sound, and temperature data from the sensors  
2. Data is transmitted wirelessly to the Raspberry Pi  
3. Raspberry Pi processes the data, logs it, and displays it on a real-time dashboard  
4. Alerts are generated if abnormal conditions are detected, allowing early fault detection

5. <img width="919" height="462" alt="image" src="https://github.com/user-attachments/assets/cfe816bf-27e5-4500-b1a6-02f465251668" />


# results
![1759154069547](https://github.com/user-attachments/assets/4d405217-105c-46f0-a19c-dbb82d3e5e99)

![1759154069592](https://github.com/user-attachments/assets/72fc235c-ca8b-4ee2-a8d6-bdf5ffee1a10)
![1759154069385](https://github.com/user-attachments/assets/ccf17789-1393-4da8-94ca-02406f6a2b9b)
<img width="655" height="409" alt="image" src="https://github.com/user-attachments/assets/cc72c966-c12e-47cd-98f3-72eca7599402" />
![1759154069244](https://github.com/user-attachments/assets/560f24b2-c163-4192-8213-1343ead85c80)



https://github.com/user-attachments/assets/f141e568-d40a-4062-82d8-28b5cdab2ae1





# Applications
- Small and medium industrial machines  
- CNC machines, motors, pumps, compressors  
- Any setup requiring real-time condition monitoring  

# Future Scope
- Integrate high level Machine Learning for predictive maintenance  
- Cloud-based dashboards for remote monitoring with integration AWS
- Mobile app alerts for on-the-go monitoring

