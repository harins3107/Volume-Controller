# ✋ Hand Tracking Module

### Real-Time Hand Detection and Finger Tracking using OpenCV & MediaPipe

![Python](https://img.shields.io/badge/Python-3.x-blue.svg)
![OpenCV](https://img.shields.io/badge/OpenCV-Computer%20Vision-green.svg)
![MediaPipe](https://img.shields.io/badge/MediaPipe-Hand%20Tracking-orange.svg)
![License](https://img.shields.io/badge/License-MIT-lightgrey.svg)

---

# 📖 Overview

**Hand Tracking Module** is a reusable Python module for real-time hand detection and landmark tracking using **OpenCV** and **Google MediaPipe**.

The module simplifies hand tracking by providing easy-to-use functions for:

- Detecting one or multiple hands
- Extracting hand landmark coordinates
- Identifying raised fingers
- Drawing hand landmarks
- Building gesture-controlled computer vision applications

It also includes a demo application that displays live hand tracking and FPS using a webcam.

---

# ✨ Features

- 🖐️ Real-time hand detection
- 👋 Multi-hand tracking support
- 📍 21 hand landmark detection
- 👍 Finger state detection (up/down)
- 🎯 Landmark coordinate extraction
- 🎨 Automatic landmark visualization
- 📷 Webcam integration
- ⚡ Lightweight and reusable module

---

# 🎯 Objectives

- Learn MediaPipe hand tracking.
- Create a reusable computer vision module.
- Simplify gesture-based application development.
- Build a foundation for Human–Computer Interaction (HCI) projects.

---

# 🛠 Technologies Used

### Programming Language

- Python

### Libraries

- OpenCV
- MediaPipe

---

# 📂 Project Structure

```text
Hand-Tracking-Module/
│
├── handTrackingModule.py
├── README.md
└── requirements.txt
```

---

# ⚙ Installation

Clone the repository:

```bash
git clone https://github.com/harins3107/Hand-Tracking-Module.git
```

Navigate into the project:

```bash
cd Hand-Tracking-Module
```

Install the required dependencies:

```bash
pip install opencv-python mediapipe
```

Or install from a requirements file:

```bash
pip install -r requirements.txt
```

---

# ▶ Running the Demo

```bash
python handTrackingModule.py
```

Press **Q** to exit the application.

---

# 🧠 Module Functions

## `handDetector()`

Initializes the hand detector with configurable parameters.

**Parameters**

- `mode`
- `maxHands`
- `detectionCon`
- `trackCon`

---

## `findHands()`

Detects hands in the current frame and optionally draws landmarks.

---

## `findPosition()`

Returns the pixel coordinates of all detected hand landmarks.

---

## `fingersUp()`

Returns the state of each finger as a list.

Example:

```python
[1, 1, 0, 0, 1]
```

Where:

- `1` → Finger is raised
- `0` → Finger is folded

---

# 🔄 Workflow

```text
Webcam Input
      │
      ▼
Frame Capture
      │
      ▼
MediaPipe Hand Detection
      │
      ▼
Hand Landmark Extraction
      │
      ▼
Finger State Detection
      │
      ▼
Draw Landmarks
      │
      ▼
Display Live Video
```

---

# 📚 Applications

This module can be used for:

- 🎨 Virtual Painter
- 🖱️ Gesture-based Drag & Drop
- ✋ Finger Counting
- 🎮 Gesture-Controlled Games
- 📽️ Presentation Controller
- 🤖 Human–Computer Interaction (HCI)
- 🧠 Sign Language Recognition
- 🎛️ Touchless Interfaces

---

# 📖 Learning Outcomes

This project demonstrates:

- Computer Vision fundamentals
- OpenCV image processing
- MediaPipe Hands solution
- Landmark detection
- Gesture recognition
- Object-oriented Python programming
- Real-time video processing

---

# 🔮 Future Enhancements

- Hand orientation detection
- Left/right hand classification
- Gesture recognition library
- Distance measurement between landmarks
- Pinch detection
- Volume and brightness control
- Air typing
- Sign language recognition

---

# 📸 Screenshots

Add screenshots or GIFs showing:

- Hand landmark detection
- Finger tracking
- Multiple hand detection
- FPS display

---

# 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a feature branch:

```bash
git checkout -b feature-name
```

3. Commit your changes:

```bash
git commit -m "Add new feature"
```

4. Push your branch:

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

# 👨‍💻 Author

**Harin S**

GitHub: https://github.com/harins3107

---

# ⭐ Support

If you found this project useful, consider giving it a ⭐ on GitHub.

---

# 📄 License

This project is licensed under the MIT License.
