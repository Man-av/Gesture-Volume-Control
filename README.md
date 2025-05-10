# 🤖 Hand Gesture Volume Control 🎶

This project allows you to control your system's volume using hand gestures. Using **MediaPipe** for hand tracking and **OpenCV** for webcam input, the system adjusts the volume based on the distance between your thumb and index finger.

## 🌟 Features
- Detects **Thumbs-Up** gesture to activate volume control.
- Detects **Thumbs-Down** gesture to deactivate volume control.
- Adjusts volume based on the distance between the thumb and index finger.

## 🛠️ Technologies Used
- Python
- MediaPipe
- OpenCV
- Pycaw

## 📥 Installation
1. Install Python 3.12
2. Install the required libraries:
    ```bash
    pip install opencv-python mediapipe pycaw numpy
    ```

## ⚙️ How to Use
1. Run the script. 
2. Show a **Thumbs-Up** to start controlling the volume. 👍
3. Show a **Thumbs-Down** to stop volume control. 👎
4. Press **ESC** to exit the application. 

## ⚠️ Note
This project does **not** use AI or machine learning models; it relies on **MediaPipe's pre-trained hand detection model** and **rule-based logic** for gesture recognition.
