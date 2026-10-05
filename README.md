# IoT Air Quality Monitor

A low-cost IoT system that measures air quality, temperature and humidity in real time and sends the data to the cloud for remote monitoring.

## Features
- Air quality (gas) sensing with MQ135
- Temperature and humidity with [DHT11 / DHT22]
- Live data on a [ThingSpeak / Blynk] dashboard
- Local display on OLED [remove if not used]

## Hardware
- [ESP8266 NodeMCU / ESP32]
- MQ135 gas sensor
- [DHT11 / DHT22]
- OLED display (I2C) [if used]
- Breadboard, jumper wires, USB power

## Software
- Arduino IDE (C/C++)
- Libraries: WiFi, DHT, Adafruit_Sensor, ThingSpeak, Wire

## How It Works
1. Sensors read air quality, temperature and humidity.
2. The microcontroller processes the readings.
3. Data is sent over Wi-Fi to [ThingSpeak/Blynk].
4. It is viewed live on the dashboard and OLED.

## Setup
1. Wire the circuit as shown in the diagram below.
2. Install the libraries via Sketch → Include Library → Manage Libraries.
3. Add your Wi-Fi name and cloud API key in the code.
4. Upload to the board and open the dashboard.

## Results
MQ135, temperature and humidity readings were displayed in real time, locally on the OLED and remotely on the cloud dashboard.

## Circuit Diagram
![Screenshot 2025-05-04 202434](https://github.com/user-attachments/assets/2ccef39a-fb74-4f72-964e-65003fa33cc9

## Future Improvements
- Add a PM2.5 sensor
- Automatic fan/filter control
- Alerts via Telegram when air quality is poor