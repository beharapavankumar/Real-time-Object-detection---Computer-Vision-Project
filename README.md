# 🎯 Real-Time Object Detection using OpenCV 
This project focuses on implementing real-time object detection using OpenCV and Haarcascade classifiers, a classical computer vision technique. The goal is to detect and highlight various objects in live video streams, including faces, eyes, pedestrians, and cars. This project is part of a broader effort in the domain of Artificial Intelligence and Computer Vision to understand object localization and tracking in real-time environments.

# 🔍 Project Overview
Using the power of OpenCV and pre-trained Haarcascade .xml files, this project performs:

Face Detection

Eye & Face Detection

Pedestrian Detection

Car Detection

Each detection type was implemented separately with its own cascade file and real-time visualization on camera feed or video input.

# ✅ Key Features
Real-time video stream processing using cv2.VideoCapture()

Object detection using detectMultiScale() function

Custom bounding boxes drawn around detected objects

Multiple Haarcascade models used:

haarcascade_frontalface_default.xml

haarcascade_eye.xml

haarcascade_fullbody.xml

haarcascade_car.xml

Optimized for CPU performance; suitable for laptops and edge devices

# 🧠 Techniques & Tools Used
OpenCV: Core library for image processing and real-time video capture

Haarcascade Classifiers: Used for object detection based on Viola-Jones algorithm

Python: For coding logic, control structures, and image transformation

Real-time feedback via live camera interface or pre-recorded video

# 🛠️ How It Works
Load a video stream or webcam using cv2.VideoCapture()

Load the Haarcascade classifier using cv2.CascadeClassifier()

Convert the frame to grayscale for detection

Detect objects using .detectMultiScale()

Draw bounding rectangles using cv2.rectangle()

Display the frame and update in real time using cv2.imshow()

# 💡 Challenges Addressed
Low-light face detection

Optimizing detection parameters (scaleFactor, minNeighbors)

Reducing false positives in pedestrian detection

Handling multiple objects in single frames

# 🎯 Applications
Surveillance systems

Driver assistance (car/pedestrian detection)

Smart doorbells and home automation

Human-computer interaction systems

🧑‍💻 Data Scientist
Behara Pavan Kumar
Exploring Artificial Intelligence through Computer Vision projects.
