# Drowsiness Detection System

This project implements a real-time drowsiness detection system using Python, OpenCV, and Dlib. It calculates the eye aspect ratio (EAR) to determine if the user's eyes are closed for a prolonged period, triggering an alert through text-to-speech.

---

## Features
- **Real-Time Face Detection**: Uses Dlib's pre-trained model for face and eye detection.
- **Eye Aspect Ratio (EAR) Calculation**: Monitors eye closure to detect drowsiness.
- **Drowsiness Detection**: Alerts the user with an audio warning.
- **Threaded Frame Capture**: Uses threading to enhance performance.

---

## Prerequisites
- Python 3.x
- Libraries:
  - OpenCV (`cv2`)
  - Dlib
  - Pyttsx3
  - Scipy
- A webcam for live video feed.
- `shape_predictor_68_face_landmarks.dat` file for Dlib's landmark prediction.

---

## Installation and Setup
1. **Install Required Libraries**:
   ```bash
   pip install opencv-python dlib pyttsx3 scipy
   
2. **Install CMake**

Dlib requires CMake to compile. Install it as follows:
	•	Windows: Download and install CMake.
 ```bash
 brew install cmake
•	Linux:
 ```bash
  sudo apt update
  sudo apt install cmake

