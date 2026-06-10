# IoT-Based Patient Health Monitoring System using ESP32 and Blynk

## Overview
This project is an IoT-based Patient Health Monitoring System that uses an ESP32 microcontroller to monitor vital health parameters and display them remotely through the Blynk IoT platform. The system enables real-time monitoring of patient health data from anywhere using a smartphone.

## Features
- Real-time health monitoring
- Remote access through Blynk mobile application
- Wi-Fi based communication
- User-friendly dashboard
- Low-cost and easy to implement
- Continuous data monitoring

## Components Required
- ESP32 Development Board
- MAX30102 Pulse Oximeter Sensor
- Temperature Sensor (LM35 / DHT11 / DS18B20)
- Breadboard
- Jumper Wires
- USB Cable
- Wi-Fi Connection
- Smartphone with Blynk App

## Software Requirements
- Arduino IDE
- Blynk IoT Platform
- ESP32 Board Package
- Required Arduino Libraries

## Block Diagram

```
Health Sensors
       |
       v
     ESP32
       |
     Wi-Fi
       |
       v
   Blynk Cloud
       |
       v
 Blynk Mobile App
```

## Working Principle

The sensors continuously monitor the patient's health parameters such as Heart Rate, SpO₂, and Body Temperature. The ESP32 processes the sensor data and sends it to the Blynk Cloud through a Wi-Fi connection. The Blynk application receives the data and displays it on a dashboard for real-time monitoring.

## Blynk Dashboard Parameters

| Parameter | Description |
|------------|-------------|
| Heart Rate | Beats Per Minute (BPM) |
| SpO₂ | Blood Oxygen Level (%) |
| Temperature | Body Temperature (°C) |

## Sample Output

| Parameter | Value |
|------------|--------|
| Heart Rate | 82 BPM |
| SpO₂ | 97 % |
| Temperature | 36.8 °C |

## Applications

- Remote Patient Monitoring
- Smart Healthcare Systems
- Home Health Monitoring
- Elderly Care
- Hospital Monitoring
- Telemedicine

## Future Enhancements

- SMS Alert System
- Emergency Notification Feature
- Cloud Database Storage
- Doctor Dashboard
- AI-Based Health Analysis

## Advantages

- Portable and Compact
- Low Power Consumption
- Real-Time Monitoring
- Wireless Communication
- Cost Effective

## Conclusion

The IoT-Based Patient Health Monitoring System using ESP32 and Blynk provides an efficient and reliable solution for remote healthcare monitoring. The system enables real-time tracking of important health parameters and improves accessibility to patient health information.

## Author

Monish Kumar

## License

This project is developed for educational and academic purposes.
