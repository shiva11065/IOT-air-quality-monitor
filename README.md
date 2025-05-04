# IOT-air-quality-monitor

##  Project Overview 
This project is an IoT -based air quality monitoring system designed to measure environmental parameters such as CO₂, particles (PM2.5), temperature and humidity. The system uses sensors connected to ESP8266 / ESP32 microcontroller and download real -time data on a cloud platform such as Thingpeak, Blynk or Firebase, allowing users to monitor air quality remotely via web or mobile control panel.
The goal is to provide an affordable and accessible vehicle to follow the quality of the indoor air, school or public places and raise awareness about environmental health.

## Components & Applications Used
Hardware Components
NodeMCU (ESP8266) or ESP32 Wi-Fi microcontroller

MQ135 Gas Sensor (for detecting air quality index/CO₂)

DHT11 / DHT22 sensor (for temperature and humidity)

OLED Display (optional for local display)

Breadboard, jumper wires, resistors

Power Supply (USB or external)

📱 Software / Apps
Arduino IDE – for writing and uploading the firmware

ThingSpeak or Blynk IoT App – for real-time data visualization

IFTTT / Telegram Bot (optional) – for alerts when pollution exceeds safe levels

Google Sheets / Firebase (optional) – for cloud data logging

##  Libraries Used for Compiling Code
Make sure to install the following libraries in the Arduino IDE:

ESP8266WiFi.h or WiFi.h – for Wi-Fi connection

Adafruit_Sensor.h

DHT.h – to read DHT11/DHT22 sensor

ThingSpeak.h – to send data to the ThingSpeak cloud

Wire.h – for I2C communication (OLED or additional sensors)

To install libraries: Go to Sketch → Include Library → Manage Libraries and search for each one.

## Project OutcomeThe quality of the air is successfully measured (MQ135), temperature and humidity in real time


displayed data both local (through OLED) and remote (via the cloud control panel)

## Conclusion
The IoT air quality monitoring project shows how integrated systems and IoT can be used to follow the environmental health. By integrating affordable cloud sensors, this system makes air quality data access and meaningful. It can be expanded to include automation (for example, activating fans or filters) or automatically learning to analyze predictions in smart city applications.
## Circuit Diagram & Simulation 
![Screenshot 2025-05-04 202434](https://github.com/user-attachments/assets/2ccef39a-fb74-4f72-964e-65003fa33cc9)


