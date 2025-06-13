# 🚗 AI-Based Driver Monitoring System

![Python](https://img.shields.io/badge/Python-3.9-blue?logo=python)
![Flask](https://img.shields.io/badge/Flask-Web%20Framework-green?logo=flask)
![OpenCV](https://img.shields.io/badge/OpenCV-RealTime-red?logo=opencv)
![Platform](https://img.shields.io/badge/Platform-Windows%20%7C%20Linux-orange)
![Status](https://img.shields.io/badge/Status-Complete-brightgreen)

An AI-powered web application that detects **driver drowsiness** and **distraction** in real-time using a webcam. The system alerts the driver through an audible beep if signs of sleepiness or inattentiveness are detected.

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

🚀 How to Run the Project Locally
Follow these simple steps to set up and run the Driver Monitoring System on your local machine.

💡 Make sure you have Python 3.8+ installed and a webcam connected.

⚙️ 1. Clone the Repository
git clone https://github.com/yourusername/driver-monitoring-system.git
cd driver-monitoring-system

📦 2. Install Required Dependencies
Use the command below to install all Python packages listed in requirements.txt.

pip install -r requirements.txt
If you’re using a virtual environment (recommended):

python -m venv venv
venv\Scripts\activate  # For Windows
source venv/bin/activate  # For Linux/macOS

pip install -r requirements.txt

🧠 3. Run the Application
Launch the Flask app by running:

python main.py
You should see output like:
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)

🌐 4. Open in Browser
🔗 Open your browser and go to:
http://127.0.0.1:5000
You’ll see the live webcam feed and detection interface.

✅ 5. Start Monitoring
Click the Start Detection button to begin monitoring for drowsiness or distraction.
Alerts will sound if unsafe behavior is detected.

