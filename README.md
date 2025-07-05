# Alcohol Detection and Engine Locking System with Fingerprint Authentication

An IoT-based safety system designed to prevent drunk driving by integrating alcohol detection, fingerprint authentication, engine control, and real-time alerting via GSM and GPS.

## Features

- Fingerprint authentication for authorized users only
- MQ3 alcohol sensor for BAC detection
- GSM/GPS module for sending alerts with live location
- Relay module for engine locking
- Buzzer and LCD for local alerts
- ESP32 microcontroller for real-time processing

## Hardware Components

- ESP32 or Arduino Uno
- MQ3 Alcohol Sensor
- R305 Fingerprint Sensor
- SIM800L GSM Module
- GPS Module
- Relay Module
- DC Motor
- Buzzer
- LCD Display (optional)
- Ignition Key Switch

## Software Requirements

- Arduino IDE 1.8.5 or later
- Embedded C
- Libraries:
  - Adafruit_Fingerprint
  - SoftwareSerial
  - TinyGPS++
  - LiquidCrystal

## Installation

1. Clone this repository:
git clone https://github.com/vishal-r-v/alcohol-detection-engine-locking-system.git
2. Open the Arduino sketch in:
software/arduino/alcohol_detection_vishal_final.ino
3. Install required libraries
4. Connect your ESP32/Arduino board
5. Upload the code using Arduino IDE

## Usage

1. Turn the ignition key
2. Authenticate using a registered fingerprint
3. System checks alcohol level using MQ3 sensor
4. If below threshold → engine (motor) starts
5. If above threshold → engine locks, buzzer sounds, alert sent via GSM with GPS location

## Folder Structure

/alcohol-detection-engine-locking-system
├── documents/
│ ├── datasheet/
│ └── report/
├── images/
│ ├── assembled/
│ ├── block-diagram/
│ └── components/
├── arduino/
├── README.md
└── LICENSE

## Documentation

See `documents/report/ALCOHOL DETECTION.docx` for complete technical report and system explanation. Sensor datasheets are in `documents/datasheet/`.

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Authors

- Vishal
- Pranav

git clone https://github.com/YOUR_USERNAME/alcohol-detection-engine-locking.git
