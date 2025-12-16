# **👤 Real-Time Face Detection Using MediaPipe & OpenCV**

This project is a real-time face detection application developed in Python using OpenCV and MediaPipe Face Detection. The system captures live video from a webcam, processes each frame, and accurately detects human faces by drawing bounding boxes around them in real time.

MediaPipe’s lightweight and efficient face detection model ensures fast performance with high accuracy, making this application suitable for real-time computer vision use cases.

## **🚀 Features**

Real-time face detection using webcam

Fast and accurate face detection with MediaPipe

Live bounding box visualization

Lightweight and efficient processing

Simple and easy-to-understand implementation

## **🛠️ Technologies Used**

Python

OpenCV

MediaPipe

Computer Vision

## **📦 Installation Steps**
1️⃣ Prerequisites

Python 3.8 or above

Working webcam

Internet connection (for first-time package installation)

2️⃣ Clone the Repository
```
git clone https://github.com/HEMAVIDAVALURU/Face-Detection.git
cd Face-Detection
```

3️⃣ Create a Virtual Environment (Optional but Recommended)
```
python -m venv venv
```

Activate it:

Windows
```
venv\Scripts\activate
```

Mac / Linux
```
source venv/bin/activate
```

4️⃣ Install Required Libraries
```
pip install opencv-python mediapipe
```


If you face issues with OpenCV, try:

```
pip install opencv-python-headless
```

5️⃣ Run the Application
```
python face_detect1.py
```

## **▶️ How to Use**

The webcam will open automatically

Faces will be detected and highlighted with bounding boxes

Press q to exit the application

## **▶️ How It Works**

Accesses the system webcam using OpenCV

Converts frames from BGR to RGB format

Uses MediaPipe Face Detection model to identify faces

Draws bounding boxes around detected faces in real time

Displays live video output until the user exits

## **📌 Use Cases**

Face detection systems

Attendance and surveillance applications

Real-time video processing

Computer vision learning projects

## **📂 Project Structure**
```
face-detection/
│
├── face_detect1.py
└── README.md
```
