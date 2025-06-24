# An-Object-Detction-Model-For-Traffic-Analysis-Using-YoloV8
# 🚦 Smart Traffic Analysis System

A real-time AI-powered system that detects, tracks, and analyzes vehicles from traffic video feeds using **YOLOv8** and the **Google Gemini API**.

The system identifies various types of vehicles (cars, bikes, buses, trucks, etc.) and extracts detailed attributes such as **make, model, color**, and partial **license plate information** using AI. It is built to support traffic monitoring, congestion detection, and smart city infrastructure.

## 🔧 Key Features
- 🎯 Real-time vehicle detection with YOLOv8  
- 🚗 Vehicle attribute extraction (make, model, color, number plate) via Gemini API  
- 📊 Traffic flow and congestion pattern analysis  
- 📹 Works with both live video streams and recorded footage  
- ⚙️ Modular and scalable design for integration into intelligent transport systems


## 🛠 Tech Stack
- **YOLOv8** – for object detection  
- **OpenCV** – for video processing and frame handling  
- **Google Gemini API** – for AI-based vehicle detail extraction  
- **PyTorch** – for deep learning backend  
- **Python** – core programming language


## 🔍 Dataset
- Trained with the **COCO dataset**  
- Enhanced using a **custom dataset** created from annotated traffic footage to handle real-world traffic scenarios


## 🌐 Future Enhancements
- Add number plate recognition (ANPR)  
- Build a real-time dashboard with alert visualization  
- Improve object tracking for dense traffic environments  
- Optimize for lightweight deployment on edge devices
