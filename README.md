# 🌊 Real-Time Underwater Seabed Biodiversity Analysis System Using an Enhanced Deep Learning CNN Framework

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/PyTorch-Deep%20Learning-red?style=for-the-badge&logo=pytorch">
  <img src="https://img.shields.io/badge/YOLO-Object%20Detection-green?style=for-the-badge">
  <img src="https://img.shields.io/badge/Computer%20Vision-Underwater-blueviolet?style=for-the-badge">
</p>

---

## 📌 Overview

The **Real-Time Underwater Seabed Biodiversity Analysis System** is a deep learning-based framework developed for detecting and analyzing underwater biodiversity using advanced object detection techniques.

Underwater environments present several challenges including:

- Low visibility
- Light absorption and scattering
- Color distortion
- Occlusion and overlapping objects

To address these issues, this project evaluates multiple YOLO-based object detection models and introduces an enhanced model called **YOLOv8NX**, designed specifically for underwater detection scenarios.

---

## 🎯 Objectives

- Detect underwater organisms in real time
- Improve object localization in low-visibility environments
- Compare state-of-the-art YOLO models
- Reduce overlapping bounding box predictions
- Enhance biodiversity monitoring and marine ecosystem analysis

---

## 🧠 Models Evaluated

| Model |
|---------|
| YOLOv5 |
| YOLOv7 |
| YOLOv8 |
| YOLOv11 |
| YOLOv8NX (Proposed Model) |

---

## 🏗️ System Architecture

```text
Dataset Collection
        │
        ▼
Data Preprocessing
        │
        ▼
YOLO Model Training
        │
        ▼
Feature Extraction
        │
        ▼
Object Detection
        │
        ▼
Performance Evaluation
        │
        ▼
Real-Time Biodiversity Analysis
```

---

## 📂 Dataset

**Dataset Source:** Roboflow Underwater Object Detection Dataset

- Total Images: 5,542
- Training Set: 3,879 Images (70%)
- Validation Set: 1,109 Images (20%)
- Test Set: 554 Images (10%)

Dataset includes:

- Fish species
- Marine organisms
- Coral structures
- Underwater objects

---

## ⚙️ Technologies Used

### Programming Languages
- Python

### Deep Learning Frameworks
- PyTorch
- Ultralytics YOLO

### Computer Vision Libraries
- OpenCV
- NumPy
- Matplotlib

### Development Tools
- Jupyter Notebook
- Google Colab
- VS Code

### Dataset Platform
- Roboflow

---

## 📊 Performance Comparison

| Model | Precision | Recall | mAP@0.5 | mAP@0.5:0.95 |
|---------|---------|---------|---------|---------|
| YOLOv5 | 82.93% | 70.11% | 76.57% | 44.65% |
| YOLOv7 | 78.20% | 60.42% | 71.51% | 40.91% |
| YOLOv11 | 69.84% | 68.91% | 71.29% | 41.51% |
| YOLOv8 | 78.40% | 74.30% | 77.10% | 44.70% |
| **YOLOv8NX** | **83.77%** | 63.53% | 62.41% | 44.22% |

### Key Findings

✅ Highest Precision achieved by YOLOv8NX (83.77%)

✅ YOLOv8 achieved highest Recall (74.30%)

✅ X-Attention mechanism improved spatial separation

✅ Better bounding box quality in cluttered underwater scenes

---

## 🔬 Proposed YOLOv8NX

The proposed YOLOv8NX model extends YOLOv8 by integrating an **X-Attention Mechanism**.

### Benefits

- Improved feature representation
- Reduced overlapping detections
- Better object localization
- Enhanced underwater robustness
- Stable detection in low-visibility conditions

---

## 📈 Evaluation Metrics

The following metrics were used:

- Precision
- Recall
- mAP@0.5
- mAP@0.5:0.95

---

## 🚀 Applications

- Marine Biodiversity Monitoring
- Underwater Object Detection
- Ocean Exploration
- Autonomous Underwater Vehicles (AUVs)
- Environmental Conservation
- Smart Marine Surveillance

---

## 👨‍💻 Authors

### Sanjey S
Department of Information Technology  
St. Joseph's Institute of Technology

### Janarthan B
Department of Information Technology  
St. Joseph's Institute of Technology

### Sam Varghese George
Department of Electronics and Communication Engineering  
St. Joseph's College of Engineering

---

## 📜 License

This project is intended for academic and research purposes.

---

## ⭐ Support

If you found this project useful, please consider giving it a ⭐ on GitHub.
