# Real-Time Hand Tracking with Python

A real-time hand tracking project using Python, OpenCV, and MediaPipe.
This program detects 21 hand landmarks (wrist + fingers) and visualizes them on a live webcam feed, highlighting key points like the wrist and fingertips. Additionally, it allows controlling your system volume based on the distance between your thumb and index finger.
---

## Demo

<img width="1232" height="745" alt="Hand Tracking Demo" src="https://github.com/user-attachments/assets/55b777b1-d6a0-4ebd-9ec5-e7d6d42f5ee7" />
<img width="753" height="592" alt="image" src="https://github.com/user-attachments/assets/c51f6e42-1bc6-48be-ad84-81fa815e91c1" />


---

## Features

- Tracks **21 hand landmarks** per hand  
- Highlights important points (wrist, thumb tip, etc.)  
- Draws connections between landmarks (bones)
- Control system volume by adjusting finger distance 
- Calculates FPS for real-time performance monitoring  
- Works with default or external webcams  

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/Gulshan-heap/CV-project.git
cd CV-project
```

## Install Dependencies
pip install opencv-python mediapipe

## Usage
python HandTracking.py

## Requirements

- Python 3.9 – 3.12
- OpenCV
- MediaPipe

