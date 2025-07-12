# helmet-detection
# 🪖 Helmet Detection using YOLOv8

A deep learning project for real-time helmet detection using the Ultralytics YOLOv8 object detection model. This project focuses on identifying whether individuals in images or videos are wearing helmets — a crucial safety compliance task in traffic and construction environments.

---

## 📌 Features

- 🧠 YOLOv8-based object detection for helmet classification
- 🗂️ Custom dataset loading and annotation support
- 📊 mAP evaluation for model performance
- 🎯 Inference on image, video, or webcam input
- 📦 Google Colab compatible with GPU acceleration

---

## 🛠️ Setup Instructions

### 1. Clone this Repository
```bash
git clone https://github.com/yourusername/helmet-detection-yolov8.git
cd helmet-detection-yolov8
2. Install Dependencies
bash
Copy
Edit
pip install -r requirements.txt
Or use Colab: Run in Google Colab

3. Download YOLOv8 Weights
bash
Copy
Edit
pip install ultralytics
📁 Directory Structure
bash
Copy
Edit
📦helmet-detection-yolov8
 ┣ 📂runs/                # Training logs and results
 ┣ 📂datasets/            # Images and annotations
 ┣ 📜helmet-detection-yolov8.ipynb  # Main training & inference notebook
 ┗ 📜README.md
