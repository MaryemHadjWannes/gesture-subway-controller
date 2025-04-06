
# 🎮 Gesture-Controlled Subway Surfers (Python + MediaPipe + OpenCV)

Control Subway Surfers using hand gestures and your webcam!
Built with Python, OpenCV, MediaPipe, and system-level keyboard events using `pynput`.

## ✨ Features
- Real-time hand gesture detection
- Maps finger count to in-game controls:
  - 1 finger → Jump
  - 2 fingers → Roll
  - 3 fingers → Right
  - 4 fingers → Left
- Launches game automatically in browser
- No keyboard needed!

## 🛠 Requirements
- Python 3.10+
- Google Chrome + ChromeDriver
- Webcam

## 🚀 Getting Started

```bash
git clone https://github.com/YOUR_USERNAME/gesture-subway-controller.git
cd gesture-subway-controller
pip install -r requirements.txt
jupyter notebook gesture_controller.ipynb
