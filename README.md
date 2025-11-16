🧠 Real-Time Object Detection using Python & OpenCV:

This project demonstrates real-time object detection using Python, OpenCV, and a pre-trained MobileNet SSD deep learning model. It identifies multiple objects inside an image or video stream and displays bounding boxes with confidence scores.

🚀 Features:

Detects 20+ common objects (chair, person, dog, car, bottle, etc.)
Lightweight and fast MobileNet SSD model
Runs in real time
Works with both images and live camera feed
Displays bounding boxes + confidence percentage
Google Colab–friendly code

📸 Sample Output

Below is one of the detection results produced by the model:

<img width="1918" height="965" alt="detection_result" src="https://github.com/user-attachments/assets/0e0d62b0-00ab-4bc8-b0d5-f9eddcf0eccc" />

Tech Stack:

Python
OpenCV
MobileNet SSD (Caffe model)
NumPy
Jupyter Notebook / Google Colab

Project Structure
realtime-object-detection/
│── models/
│   ├── MobileNetSSD_deploy.caffemodel
│   └── MobileNetSSD_deploy.prototxt
│── sample_output/
│   └── detection_result.jpg
│── realtimeobjectdetection.ipynb
│── requirements.txt
│── README.md


▶️ How to Run Locally
1️⃣ Install dependencies
pip install opencv-python numpy imutils

2️⃣ Download MobileNet SSD Model Files

Place the following into the models/ folder:

MobileNetSSD_deploy.prototxt

MobileNetSSD_deploy.caffemodel

(You can get them from the official OpenCV GitHub.)

3️⃣ Run the code

Run the notebook:

realtimeobjectdetection.ipynb


or your Python script (if added):

python detect.py

🧩 How It Works:

Load MobileNet SSD model

Capture frame from image/video

Preprocess frame into blob

Run forward pass through the network

Extract class labels + confidence

Draw bounding boxes with labels

Display the output frame in real time

🎯 Results:

The system achieved high accuracy for objects like chairs, tables, people, and other COCO categories. It is fast, lightweight, and suitable for:

Real-time monitoring

Smart surveillance

Robotics

IoT vision systems

Object counting & tracking applications

📘 Learning Outcomes:

Implementing real-time object detection

Understanding neural network forward pass

Using pre-trained models with OpenCV

Visualizing detection results

Handling video frames efficiently




