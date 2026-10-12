# 🚨 Emergency Vehicle Priority Detection Using YOLOv8

<p align="center">
  <strong>AI-Powered Emergency Vehicle Detection for Intelligent Traffic Monitoring</strong>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?logo=python&logoColor=white" alt="Python"/>
  <img src="https://img.shields.io/badge/YOLOv8-Object%20Detection-00FFFF" alt="YOLOv8"/>
  <img src="https://img.shields.io/badge/OpenCV-Computer%20Vision-green?logo=opencv&logoColor=white" alt="OpenCV"/>
  <img src="https://img.shields.io/badge/Flask-Web%20Application-black?logo=flask&logoColor=white" alt="Flask"/>
</p>

## 📌 Overview

Emergency vehicles such as ambulances, fire trucks, and police vehicles need to reach their destinations quickly. Traffic congestion can delay emergency response and create serious challenges for road safety.

This project explores the use of **YOLOv8 object detection and computer vision** to identify emergency vehicles in traffic or CCTV videos. The application uses Python, OpenCV, and Flask to process video footage and generate an annotated output video.

## ✨ Key Features

- 🚑 Emergency vehicle detection from supported video footage
- 🎥 Frame-by-frame video processing using YOLOv8
- 🧠 AI-based object detection
- 🌐 Flask-based web interface for video uploads
- 📹 Annotated video output with detection bounding boxes
- ⚙️ Modular Python code for detection and application logic

## 🛠️ Technology Stack

| Technology | Purpose |
|---|---|
| Python | Core application development |
| YOLOv8 | Object detection |
| OpenCV | Video reading, frame processing, and output generation |
| Flask | Web application |
| Ultralytics | YOLO model integration |
| NumPy | Numerical and array operations |

## 🏗️ How It Works

1. **Upload:** The user provides a supported traffic or CCTV video through the web interface.
2. **Read frames:** OpenCV reads the video frame by frame.
3. **Detect objects:** The YOLOv8 model analyzes frames and predicts objects based on its trained classes.
4. **Annotate:** Detected objects and their bounding boxes are drawn on the frames.
5. **Generate output:** The processed frames are combined into an annotated video for review.

> **Important:** The model detects only the classes it was trained to recognize. Reliable ambulance, fire-truck, and police-vehicle detection depends on the model's training data and class configuration.

## 📂 Repository Structure

The following reflects the files visible in the current repository:

```text
EmergencyVehiclePriorityDetection/
├── README.md
├── app.py
├── detect.py
├── utils.py
├── requirements.txt
├── yolov8n.pt
└── bus.jpg
```

## ⚙️ Installation and Setup

### Prerequisites

- Python installed on your system
- pip package manager
- Git
- Sufficient storage for the model and video files

### 1. Clone the repository

```bash
git clone https://github.com/parveenbhanu2005/EmergencyVehiclePriorityDetection.git
cd EmergencyVehiclePriorityDetection
```

### 2. Create a virtual environment

```bash
python -m venv venv
```

### 3. Activate the environment

**Windows:**

```bash
venv\Scripts\activate
```

**Linux/macOS:**

```bash
source venv/bin/activate
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Run the application

```bash
python app.py
```

If `app.py` starts a Flask development server, open the local URL displayed in your terminal, commonly `http://127.0.0.1:5000`.

> If your application uses a different startup command or port, follow the configuration in your actual `app.py` file.

## ▶️ Usage

1. Start the application using the appropriate command.
2. Open its local web interface.
3. Upload a supported traffic video if the upload feature is configured.
4. Allow the application to process the video.
5. Review the annotated output, including any detected objects and bounding boxes.

## 📸 Screenshots and Demo

Add screenshots of your actual application and detection output here.

For example:

- Web application upload page
- Input traffic video
- Annotated video with detection boxes
- Final output screen

## 🔮 Future Improvements

- Integration with live CCTV streams
- Improved detection using a suitable emergency-vehicle dataset
- Object tracking across consecutive frames
- Traffic signal prioritization integration
- Detection logs and analytics dashboard
- Performance evaluation using precision, recall, and mAP
- Deployment to a suitable cloud or edge platform

## 👨‍💻 Developer

**B. Parveen Bhanu**

B.Tech — Computer Science Engineering (Cyber Security)  
Rajeev Gandhi Memorial College of Engineering & Technology, Andhra Pradesh

- [GitHub Profile](https://github.com/parveenbhanu2005)
- [LinkedIn](https://www.linkedin.com/in/parveen-bhanu-bandisula/)
- [Portfolio](https://parveenbhanu-portflio.netlify.app/)

---

*Developed as an AI and computer vision project for exploring emergency vehicle detection in traffic monitoring systems.*
