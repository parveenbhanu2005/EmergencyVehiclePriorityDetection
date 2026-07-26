# 🚑 Emergency Vehicle Priority Detection using YOLOv8

An AI-powered web application that detects emergency vehicles from CCTV or uploaded traffic videos using the YOLOv8 object detection model. The system processes videos in real time, identifies emergency vehicles, and generates an annotated output video.

---

## 📌 Project Overview

Emergency vehicles such as ambulances, fire trucks, and police vehicles often face delays due to traffic congestion. This project aims to assist intelligent traffic management systems by automatically detecting emergency vehicles from CCTV footage using Artificial Intelligence.

---

## ✨ Features

- 🚑 Detects emergency vehicles from uploaded videos
- 🎥 Processes CCTV/traffic videos using YOLOv8
- 📦 Flask-based web application
- 🖥️ Simple and user-friendly interface
- 📹 Generates an annotated output video
- ⚡ Fast and efficient object detection

---

## 🛠️ Technologies Used

- **Programming Language:** Python
- **Framework:** Flask
- **AI Model:** YOLOv8 (Ultralytics)
- **Libraries:**
  - OpenCV
  - Ultralytics
  - NumPy
  - Flask

---

## 📂 Project Structure

```
EmergencyVehiclePriorityDetection/
│
├── backend/
│   ├── app.py
│   ├── detect.py
│   ├── templates/
│   ├── static/
│   │   └── output/
│   └── uploads/
│
├── dataset/
├── models/
├── requirements.txt
├── README.md
└── yolov8n.pt
```

---

## 🚀 Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/EmergencyVehiclePriorityDetection.git
cd EmergencyVehiclePriorityDetection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the virtual environment

**Windows**

```bash
venv\Scripts\activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python backend/app.py
```

---

## ▶️ Usage

1. Open the Flask application in your browser.
2. Upload a traffic or CCTV video.
3. The YOLOv8 model processes each frame.
4. Emergency vehicles are detected and highlighted.
5. The processed output video is generated and displayed.

---

## 📸 Output

The application detects emergency vehicles and draws bounding boxes around them in the processed video.

---

## 🎯 Future Enhancements

- Live CCTV camera integration
- Smart traffic signal control
- Vehicle tracking using ByteTrack/DeepSORT
- Email/SMS alerts
- Cloud deployment
- Detection analytics dashboard

---

## 👨‍💻 Developed By

**B. Parveen Bhanu**

B.Tech – Computer Science Engineering (Cyber Security)

Rajeev Gandhi Memorial College of Engineering & Technology

---

## 📄 License

This project is developed for educational and academic purposes.
