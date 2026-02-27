# ODS
🚀 Real-Time Object Detection System

A Real-Time Object Detection System built using OpenCV’s Deep Neural Network (DNN) module and a pre-trained SSD MobileNet V3 model trained on the COCO dataset.

This application captures live video from a webcam, detects multiple objects in real time, and displays bounding boxes along with object labels and confidence scores.

🔍 Features

🎥 Real-time webcam object detection.

📦 Detects 80+ object categories (COCO dataset).

🟢 Displays bounding boxes around detected objects.

🏷️ Shows object class names with confidence percentage.

⚡ Fast and lightweight detection using MobileNet.

🛠️ Technologies Used

Python

OpenCV (cv2)

Deep Learning (OpenCV DNN Module)

SSD (Single Shot Detector)

MobileNet V3

COCO Dataset

🧠 How It Works

The system captures live video input from the webcam.

Each video frame is passed through a pre-trained SSD MobileNet model.

The model detects objects and returns:

Class ID

Confidence score

Bounding box coordinates

Detected objects are highlighted with bounding boxes and labeled with their respective class names and confidence scores.

The system runs continuously until the user presses 'q' to exit.

📂 Project Structure
├── main.py
├── coco.names
├── frozen_inference_graph.pb
├── ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt
└── README.md
▶️ Installation & Usage
1️⃣ Install Dependencies
pip install opencv-python
2️⃣ Run the Application
python main.py

Press 'q' to stop the application.
