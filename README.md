# 🚗 YOLOv8-ByteTrack Vehicle Analytics System

An intelligent AI-powered system for real-time vehicle detection, tracking, and counting using deep learning and computer vision.

---

## 📌 Overview

This project leverages **YOLOv8 (Ultralytics)** for object detection and **ByteTrack** for multi-object tracking to build a real-time vehicle analytics system.

It processes video streams, tracks vehicles with unique IDs, and counts them when crossing a predefined virtual line.

---

## 🎯 Key Features

* 🚘 Real-time vehicle detection using YOLOv8
* 🔄 Multi-object tracking with ByteTrack
* 🆔 Unique ID assignment per vehicle
* 📊 Line-crossing based vehicle counting
* 📦 Class-wise counting (car, bus, truck, etc.)
* 🎥 Annotated output video generation
* ⚡ Optimized for performance and scalability

---

## 🧠 Tech Stack

| Category        | Technology                  |
| --------------- | --------------------------- |
| Language        | Python                      |
| Detection       | YOLOv8 (Ultralytics)        |
| Tracking        | ByteTrack                   |
| Computer Vision | OpenCV                      |
| Environment     | Google Colab / Local System |

---

### Workflow:

1. Input video is processed frame-by-frame
2. YOLOv8 detects vehicles
3. ByteTrack assigns unique IDs
4. Virtual line is applied
5. Vehicles crossing line are counted
6. Output video is generated with annotations

---

## ⚙️ Installation

```bash
pip install ultralytics
pip install opencv-python
```

---

## ▶️ Usage

```bash
python vehicleCounting.py
```

### Steps:

* Upload your video file
* Update video path in code
* Run the script
* Output video will be generated

---

## 📊 Output Features

* Bounding boxes around vehicles
* Vehicle class labels
* Unique tracking IDs
* Real-time counting display

---

## 🔬 Core Logic

* Uses **YOLOv8 large model (`yolo11l.pt`)** for high accuracy
* Tracking handled via `model.track()` (ByteTrack)
* Vehicles counted only once using unique IDs
* Virtual line ensures accurate counting

---

## 🚀 Future Enhancements

* 🌐 Web dashboard (React + Flask)
* 📈 Real-time analytics & graphs
* 🚦 Traffic density estimation
* 🛰 Smart city integration
* 🎯 DeepSORT integration for advanced tracking
* ⚡ GPU optimization

---

## 🧑‍💻 Author

**Dhruvil Dave**
AI/ML Developer | LLM & Deep Learning Enthusiast

---

## ⭐ Why This Project Matters

* Real-world traffic monitoring use case
* Combines AI + Computer Vision + Tracking
* Scalable for smart city applications
* Strong portfolio project for AI/ML roles

---

## 📜 License

This project is licensed under the MIT License.

---
