# Hand Gesture-Based Volume Control

This project is a real-time system that uses hand gestures to control the system volume. It leverages **MediaPipe** for hand tracking, **OpenCV** for webcam input, and **Pycaw** to interface with the system's audio control.

## ✨ Features
- Detects thumbs-up gesture to start volume control
- Detects thumbs-down gesture to stop volume control
- Adjusts system volume based on the distance between thumb and index finger
- Real-time feedback with visual landmarks on webcam feed

## 🛠️ Technologies Used
- Python
- MediaPipe
- OpenCV
- Pycaw
- NumPy
- comtypes (for audio interface)

## 🚀 How It Works
1. The system waits for a thumbs-up gesture to activate.
2. Once active, it calculates the distance between thumb and index finger to control volume.
3. A thumbs-down gesture stops the control loop.
4. The ESC key can also be used to exit the application.

## 🔧 Requirements
- Python 3.12
- OpenCV
- MediaPipe
- Pycaw
- comtypes

You can install dependencies using:

```bash
pip install opencv-python mediapipe pycaw comtypes numpy
