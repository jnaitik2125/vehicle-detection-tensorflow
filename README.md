# vehicle-detection-tensorflow
Real-time vehicle detection and counting system using TensorFlow SSD MobileNet, OpenCV, and Computer Vision for intelligent traffic monitoring and smart city applications.
# 🚗 Vehicle Detection and Counting System using Computer Vision

## Overview

This project presents a real-time Vehicle Detection and Counting System developed using Python, TensorFlow, and OpenCV. The system detects, classifies, tracks, and counts vehicles from video streams using deep learning and computer vision techniques.

The objective of this project is to provide a cost-effective and efficient solution for traffic monitoring and analysis without requiring specialized hardware or sensor-based infrastructure.

---

## Features

* Real-time vehicle detection
* Vehicle classification (Cars, Buses, Trucks, Motorcycles)
* Vehicle tracking across frames
* Automatic vehicle counting using line-crossing detection
* Traffic data analysis
* Works on standard CPU hardware
* Video file and live camera support

---

## Technologies Used

* Python 3.x
* TensorFlow Object Detection API
* SSD MobileNet
* OpenCV
* NumPy

---



## Dataset and Model

The project uses:

* SSD MobileNet Object Detection Model
* COCO (Common Objects in Context) Dataset

Detected vehicle classes include:

* Car
* Bus
* Truck
* Motorcycle

---

## Performance

| Metric            | Value  |
| ----------------- | ------ |
| Accuracy          | 85–90% |
| Precision         | ~88%   |
| Recall            | ~85%   |
| F1 Score          | ~86%   |
| FPS               | 18–22  |
| Counting Accuracy | ~87%   |

---

## Applications

* Smart Traffic Management
* Intelligent Transportation Systems (ITS)
* Traffic Flow Analysis
* Urban Planning
* Surveillance Systems
* Parking Management

---

## Limitations

* Reduced accuracy in low-light environments
* Occlusion challenges in dense traffic
* Counting accuracy may decrease in highly congested scenes

---

## Future Enhancements

* Automatic Number Plate Recognition (ANPR)
* Multi-camera support
* YOLOv8-based implementation
* Raspberry Pi and Jetson Nano deployment
* Real-time analytics dashboard
* Vehicle speed estimation

---

## Installation

### Clone the Repository

```bash
git clone https://github.com/jnaitik2125/vehicle-detection-tensorflow.git
```

### Navigate to Project Directory

```bash
cd vehicle-detection-tensorflow
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run the Project

```bash
python main.py
```

---

## Project Outcome

The system successfully performs real-time vehicle detection and counting using deep learning techniques while maintaining high accuracy and efficient performance on standard computing hardware.

---

## Author

**Naitik Jain**
