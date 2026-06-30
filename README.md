## Overview
This project performs real-time facial emotion recognition using a webcam. It detects faces and classifies emotions such as Happy, Sad, Angry, Neutral, and more.

## Features
- Real-time webcam emotion detection
- Face detection using MTCNN
- Emotion classification using PyTorch
- CPU-compatible implementation
- Easy to run

## Technologies Used
  - Python 3.9
  - PyTorch 2.8.0
  - Torchvision 0.23.0
  - OpenCV 4.13.0
  - NumPy 2.0.2
  - Facial Emotion Recognition 0.3.4
  - FaceNet-PyTorch 2.5.3

## Installation

--py -3.9 -m pip install torch==2.8.0 torchvision==0.23.0
--py -3.9 -m pip install opencv-python==4.13.0.92
--py -3.9 -m pip install facial-emotion-recognition==0.3.4
--py -3.9 -m pip install facenet-pytorch==2.5.3

## Architecture

Webcam Input
      ↓
Video Frame Capture (OpenCV)
      ↓
Face Detection (MTCNN)
      ↓
Face Preprocessing
(Resize & Normalize)
      ↓
Emotion Recognition (PyTorch)
      ↓
Emotion Prediction
(Happy / Sad / Angry / Neutral / Surprise)
      ↓
Display Result
(OpenCV Output Window)
