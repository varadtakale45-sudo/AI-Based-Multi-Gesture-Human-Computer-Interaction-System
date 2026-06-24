# AI-Based Gesture Controlled Human Computer Interaction System Using Computer Vision and MediaPipe

## License

This project is licensed under the MIT License. Feel free to use, modify, distribute, and share this project with proper attribution.

---

## Overview

The AI-Based Gesture Controlled Human Computer Interaction System is a computer vision project that enables users to control various system functions using hand gestures detected through a webcam. The system utilizes real-time hand landmark detection provided by MediaPipe and image processing techniques from OpenCV to interpret hand gestures and perform corresponding actions such as adjusting screen brightness, controlling system volume, and capturing screenshots.

## Problem Statement

Traditional computer interaction relies heavily on keyboards, mice, and touchscreens. This project demonstrates a touchless interaction system that allows users to perform common computer operations using hand gestures.

## Objectives

- Develop a real-time hand gesture recognition system.
- Implement gesture-based brightness control.
- Implement gesture-based volume control.
- Implement screenshot capture.
- Demonstrate AI and Computer Vision concepts.

## Features

### Brightness Control
Pinch gesture controls system brightness dynamically.

### Volume Mute
Fist gesture mutes system audio.

### Volume Increase
Open palm gesture increases system volume.

### Screenshot Capture
Victory sign captures and saves a screenshot.

### Real-Time Processing
All gestures are recognized in real-time using a webcam.

## Technologies Used

- Python
- OpenCV
- MediaPipe
- NumPy
- Screen Brightness Control
- PyAutoGUI
- PyCAW
- Comtypes

## System Requirements

### Hardware
- Webcam
- 4 GB RAM or higher
- Intel i3 or higher

### Software
- Python 3.10+
- Windows OS

## Installation

```bash
pip install opencv-python mediapipe numpy screen-brightness-control pyautogui comtypes pycaw
```

## Project Structure

```text
GestureController/
│
├── gesture_controller.py
├── hand_landmarker.task
├── requirements.txt
├── README.md
└── screenshots/
```

## Working Principle

1. Webcam captures live video.
2. MediaPipe detects hand landmarks.
3. Gesture is identified using landmark positions.
4. Corresponding action is executed.
5. Results are displayed on-screen.

## Gesture Mapping

| Gesture | Action |
|----------|---------|
| Pinch | Brightness Control |
| Fist | Mute Volume |
| Open Palm | Volume Up |
| Two Fingers | Screenshot |

## Applications

- Smart Human Computer Interaction
- Touchless Interfaces
- Smart Homes
- Accessibility Systems
- Presentation Control

## Advantages

- Contactless operation
- Real-time performance
- User friendly
- Low hardware requirements

## Limitations

- Sensitive to lighting conditions
- Depends on webcam quality
- Limited gesture set

## Future Scope

- Volume Down Gesture
- PowerPoint Navigation
- Media Controls
- Smart Home Integration
- Multi-Hand Detection
- Custom Gesture Training

## Results

The system successfully performs real-time gesture recognition and executes brightness control, volume control, and screenshot capture with minimal latency.

## Conclusion

This project demonstrates the practical use of Artificial Intelligence, Computer Vision, and Human Computer Interaction techniques to build an effective touchless computer control system.

📄 License
This application is open-source software distributed under the MIT License.
