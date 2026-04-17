# Real-Time-Object-Tracking-System-Raspberry-Pi-OpenCV
# 🎯 Real-Time Object Tracking System (Raspberry Pi + OpenCV)

## 📌 Overview
This project implements a real-time object tracking system using Raspberry Pi and OpenCV.  
It detects and tracks objects (based on color or AI models) from live camera feed.

Real-time object detection and tracking can be efficiently implemented on Raspberry Pi using OpenCV and deep learning models [[7](https://heartbeat.comet.ml/real-time-object-detection-on-raspberry-pi-using-opencv-dnn-98827255fa60)].

---

## 🚀 Features
- Real-time video processing  
- Color-based object detection (HSV)  
- Bounding box tracking  
- Lightweight and optimized for Raspberry Pi  
- Extendable to AI models (YOLO, MobileNet)

---

## 🛠️ Tech Stack
- Raspberry Pi (3/4/5)  
- Pi Camera / USB Camera  
- Python  
- OpenCV  

---

## 📂 Project Structure
rpi-object-tracking/
│── main.py
│── requirements.txt
│── README.md

---

## ⚙️ Installation
bash
sudo apt update
sudo apt install python3-opencv
pip install numpy
python3 main.py


🔄 Workflow
Capture video frame
Convert to HSV
Apply color mask
Detect contours
Draw bounding box
Display output
