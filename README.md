# Bangladesh Traffic Violation Detection 🚦

A computer vision–based traffic monitoring system developed during my **Industrial Attachment at Brain Machine AI**. The project focuses on detecting common motorcycle traffic violations using deep learning and computer vision techniques.

## Features

* 🏍️ **Motorcycle & Person Detection** using YOLOv8
* 🪖 **Helmet / No-Helmet Detection**
* 👥 **Single, Double & Triple Riding Detection**
* 🎯 **Rider–Motorcycle Association** using IoU and proximity
* 🎥 **Multi-object Tracking** using ByteTrack
* 🔢 **Bangla License Plate Detection & Recognition (ANPR)**
* 📐 **Camera Perspective / Angle Analysis**
* 📝 **Structured Traffic Violation Reporting**

## Pipeline

The system follows a multi-stage pipeline:

```text
Traffic Image / Video
        ↓
YOLOv8 Detection
        ↓
Motorcycle & Person Association
        ↓
ByteTrack Tracking
        ↓
Rider Count
        ↓
Helmet Violation Detection
        ↓
License Plate Detection
        ↓
Bangla ANPR / OCR
        ↓
Traffic Violation Report
```

## Technologies Used

* Python
* YOLOv8
* OpenCV
* Ultralytics
* ByteTrack
* EasyOCR
* PyTorch
* Roboflow
* Kaggle

## Datasets

The project uses multiple publicly available datasets for different components, including:

* Helmet and license plate detection datasets
* Triple-riding detection datasets
* Rider-count datasets
* **Bangla LPDB-A** for Bangla license plate recognition

## Project Structure

```text
├── traffic-violation-detection.ipynb
├── README.md
└── datasets/
```

## Objective

The main objective is to explore how deep learning and computer vision can be combined to build an automated traffic monitoring system capable of identifying motorcycle-related violations and extracting relevant vehicle information.

> Developed as part of my Industrial Attachment at **Brain Machine AI**.
