# 🛡️ SafeVisionAI
Smart Surveillance for Safer Spaces

SafeVisionAI is an AI-powered real-time surveillance system built using Computer Vision (CV), Audio Recognition, and Machine Learning (ML) to detect suspicious human activity and respond to emergency voice commands like “Help.” The system captures evidence (photo/video) and sends instant alerts to authorities or a monitoring dashboard.

## 🚀 Key Features

- 🔍 **Suspicious Activity Detection**  
  Detects dangerous actions like dragging, falling, or physical violence using YOLOv5.

- 🎙️ **Voice Command Activation**  
  Recognizes emergency phrases like “Help” to trigger alerts using audio recognition.

- 📸 **Real-Time Frame Capture**  
  Captures important video frames when suspicious activity or voice is detected.

- 📲 **Telegram Alert System**  
  Sends immediate alerts (text + image) to a Telegram bot to simulate police notification.

- 🖥️ **Flask-Based Monitoring Dashboard**  
  A simple web interface to view captured frames, timestamps, and system status logs in real-time — helping authorities or users to review suspicious events quickly and visually.


## ⚙️ Tech Stack

| Component             | Tool/Library                        |
|----------------------|-------------------------------------|
| Object Detection      | [YOLOv5](https://github.com/ultralytics/yolov5), OpenCV |
| Audio Recognition     | Vosk, SpeechRecognition             |
| Backend & API Server  | Flask                               |
| Alert System          | Telegram Bot API                    |
| Dashboard UI          | HTML, Jinja2, Bootstrap (via Flask) |
| Deployment (MVP)      | Google Colab (for training), Render (for dashboard) |


## 📁 Folder Structure
SafeVisionAI/
├── detection/
│   └── object_detection.py
├── audio/
│   └── voice_command.py
├── alert/
│   └── send_telegram.py
├── models/
├── main.py
├── requirements.txt
└── README.md


## ✅ How It Works (MVP)
Camera stream is monitored in real-time.

Model detects specific suspicious activities or voice triggers.

System captures image frames and logs the time of event.

Alert is sent via Telegram bot to notify the response team.

## 🧠 Future Enhancements
Accident/crash detection with vehicle details

Integration with hospital alert systems

Face recognition and ID verification

Drone-based surveillance and GPS tracking

## 📽️ Demo
Coming Soon...

## 👨‍💻 Developed By
Priyanshu Kothari
B.Tech Final Year Student
Aspiring AI/ML Engineer
