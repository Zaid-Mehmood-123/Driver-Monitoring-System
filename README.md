# 🚗 AI-Based Driver Monitoring System

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-green?logo=flask)
![OpenCV](https://img.shields.io/badge/OpenCV-RealTime-red?logo=opencv)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

An AI-powered web application that detects **driver drowsiness** and **distraction** in real-time using a webcam. The system alerts the driver through an audible beep if signs of sleepiness or inattentiveness are detected.

---
---

> 🚗 *AI That Watches Over You While You Drive*

---

## 🔍 Features

- 🎥 Real-time video stream via webcam
- 💤 Drowsiness detection (eye closure)
- 👀 Distraction detection (looking away)
- 🔔 Audio alert system
- 🌐 Flask-based web interface
- 📦 Modular and scalable folder structure
- ⚙️ Uses OpenCV, MediaPipe, and pre-trained models

---

## 🛠️ Technologies Used

- **Python 3**
- **OpenCV** – for webcam video processing
- **MediaPipe** – for face and eye landmark detection
- **Flask** – for web framework
- **Pygame** – for sound alerts

---

## 📁 Folder Structure

driver_monitoring_system/
├── app/
│ ├── static/ # CSS and JS 
│ ├── templates/
│ │ └── index.html # Frontend UI
│ ├── utils/
│ │ ├── drowsiness_detector.py
│ │ ├── distraction_detector.py
│ │ └── alert_manager.py
│ ├── video_stream.py # Video feed and detection loop
│ └── routes.py # Flask routes and logic
│
├── models/
│ ├── yolo_model/ # YOLO model files (optional)
│ ├── face_landmarks/ # MediaPipe configs
│ └── phone_model/ # Skipped in final version
│
├── main.py # App entry point
├── requirements.txt # Python dependencies
└── README.md


---

## 🚀 How to Run

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/driver-monitoring-system.git
   cd driver-monitoring-system
