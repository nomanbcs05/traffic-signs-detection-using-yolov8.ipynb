# traffic-signs-detection-using-yolov8.ipynb
This project applies the YOLOv8 (You Only Look Once) deep learning model for the automatic detection and recognition of traffic signs. Accurate identification of road signs is vital for intelligent transportation systems (ITS), driver assistance technologies, and autonomous vehicles, enhancing safety and ensuring compliance with traffic regulations.
# 🚦 Traffic Signs Detection using YOLOv8

## 📘 Overview
This project applies the **YOLOv8 (You Only Look Once)** deep learning model for the **automatic detection and recognition of traffic signs**.  
Accurate identification of road signs is vital for **intelligent transportation systems (ITS)**, **driver assistance technologies**, and **autonomous vehicles**, enhancing safety and ensuring compliance with traffic regulations.

The **YOLOv8** model, developed by **Ultralytics**, offers exceptional **speed and real-time detection accuracy**.  
This notebook demonstrates how YOLOv8 can effectively detect and classify multiple traffic sign types in various environments, including different lighting, viewing angles, and weather conditions.

## 📊 Dataset
- Dataset: [Traffic Signs Dataset (Kaggle)](https://www.kaggle.com/datasets)
- Format: YOLO annotations (images + labels)
- Includes various traffic signs such as speed limits, warnings, and prohibitory signs.

## 🧠 Model Details
- Framework: **PyTorch (Ultralytics YOLOv8)**
- Image size: **640×640**
- Epochs: **100**
- Batch size: **16**
- Optimizer: **Adam**
- Learning rate: **0.001**

## ⚙️ How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<your-username>/traffic-signs-detection-yolov8.git
