# Vision-Based Multi-Finger Gesture Control System

This project implements a real-time, contactless hand gesture control system using
MediaPipe and OpenCV on a Python host, interfaced with an ESP32 microcontroller
to control servo motors and LED indicators.

## 🔍 Project Overview
- Real-time hand and finger detection using MediaPipe Hands
- Individual finger OPEN/CLOSE detection
- Low-latency serial (UART) communication
- Independent control of 5 servo motors and LEDs
- Designed for industrial automation and assistive applications

## 🧠 Technologies Used
**Software**
- Python
- OpenCV
- MediaPipe Hands
- PySerial

**Hardware**
- ESP32
- SG90 Servo Motors (x5)
- LEDs with current-limiting resistors
- USB Webcam

## ⚙️ System Architecture
1. Webcam captures hand gestures
2. Python processes landmarks using MediaPipe
3. Finger states encoded into serial commands
4. ESP32 parses commands
5. Servos and LEDs actuated in real time

## 📊 Performance
- Gesture recognition accuracy: ~90%
- End-to-end latency: 80–120 ms
- Stable operation over 15 minutes continuous use

## 📁 Repository Structure
- `Python_Code/` – Gesture recognition and communication logic
- `ESP32_Code/` – Embedded firmware
- `Report/` – Full technical report (PDF)
- `Project_Images/` – System diagrams and hardware photos

## 🚀 Applications
- Industrial automation (contactless control)
- Assistive robotics
- Smart home interfaces
- Educational and research platforms
