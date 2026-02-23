# ODS
🚀 Real-Time Object Detection System
This project is a Real-Time Object Detection System built using OpenCV’s Deep Neural Network (DNN) module and a pre-trained SSD MobileNet V3 model trained on the COCO dataset.
The system captures live video from the webcam, detects multiple objects in real time, and displays bounding boxes along with object labels and confidence scores.

🔍 Features
🎥 Real-time webcam object detection
📦 Detects 80+ object categories (COCO dataset)
🟢 Displays bounding boxes around detected objects
🏷️ Shows object class name and confidence percentage
⚡ Fast and lightweight detection using MobileNet

🛠️ Technologies Used
Python
OpenCV (cv2)
Deep Learning (DNN module)
SSD (Single Shot Detector)
MobileNet V3
COCO Dataset

🧠 How It Works
The system captures video input from the webcam.
Each frame is passed through a pre-trained SSD MobileNet model.
The model detects objects and returns:
Class ID
Confidence score
Bounding box coordinates
The detected objects are highlighted with bounding boxes and labels in real time.

📂 Model Details
Architecture: SSD MobileNet V3
Dataset: COCO (Common Objects in Context)
Framework: TensorFlow (pre-trained model)

🎯 Applications
Smart surveillance systems
Automated monitoring
Human detection systems
AI-based vision applications
Real-time object tracking foundations

▶️ How to Run
Install required libraries:
pip install opencv-python
Ensure the following files are in the same directory:
main.py
coco.names
frozen_inference_graph.pb
ssd_mobilenet_v3_large_coco_2020_01_14.pbtxt

Run:
python main.py
Press 'q' to exit.
