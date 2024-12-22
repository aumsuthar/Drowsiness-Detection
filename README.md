# Drowsiness Detection System

This project implements a real-time drowsiness detection system using Python, OpenCV, and Dlib. It detects the eye aspect ratio (EAR) to determine if the user's eyes are closed for a prolonged period, triggering an alert through text-to-speech if drowsiness is detected.

## Features
- **Real-Time Face Detection**: Utilizes Dlib's face detection model to identify faces in the video feed.
- **Eye Aspect Ratio (EAR) Calculation**: Detects and calculates EAR to assess eye closure.
- **Drowsiness Detection**: Alerts the user via audio when drowsiness is detected.
- **Multi-threaded Frame Capture**: Enhances performance by using threading for video frame capture.

## Prerequisites
- Python 3.x
- Libraries:
  - OpenCV (`cv2`)
  - Dlib
  - Pyttsx3
  - Scipy
- A webcam for video feed
- `shape_predictor_68_face_landmarks.dat` file for Dlib (place it in the appropriate directory and update the path in the code).

## Installation
1. Install the required libraries:
   ```bash
   pip install opencv-python dlib pyttsx3 scipy
