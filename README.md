# Gesture-Based Volume Control Using Hand Tracking 🎛️🖐️

This project enables touchless control of system volume using hand gestures, leveraging MediaPipe, OpenCV, and **PyAutoGUI**. The distance between your **thumb and index finger** is used to control the volume — the farther apart they are, the higher the volume.

## 📸 Demo
![WhatsApp Image 2025-05-29 at 20 21 02_8504e4e0](https://github.com/user-attachments/assets/d02b6c8f-7bc0-4fc3-b577-b10888af4473)


---

## 🚀 Features
- Real-time hand tracking using webcam
- Detects thumb and index fingertip positions
- Calculates distance between fingers to control volume
- Uses PyAutoGUI to simulate volume key presses
- Smooth and responsive interaction

---

## 🛠️ Technologies Used
- **Python 3**
- **OpenCV**
- **MediaPipe**
- **PyAutoGUI**

---

Install the required libraries:
pip install opencv-python mediapipe pyautogui

---

▶️ How to Run

python gesture_volume_control.py

Make sure your webcam is connected.

Show your hand in front of the camera.

Move your thumb and index finger apart to increase volume.

Move them closer to decrease volume.

Press ESC to exit.
