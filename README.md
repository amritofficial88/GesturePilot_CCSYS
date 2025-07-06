#  GesturePilot: Computer Control via Hand Movements  
> A touchless interaction system powered by hand tracking

## Overview

**GesturePilot** is an intuitive hand-gesture-based interface that lets you control your computer without touching a keyboard or mouse. Built with computer vision and real-time hand tracking, it delivers seamless interaction for accessibility, hygienic environments, or just a bit of futuristic fun.

## Features

- **Volume Control**  
  Adjust your system’s volume by varying finger distance.

- **Finger Counting**  
  Real-time detection of raised fingers.

- **Gesture Recognition**  
  Recognize predefined hand gestures for triggering specific actions.

- **Virtual Cursor**  
  Control your mouse using your index finger as a pointer.


## ⚙️ Tech Stack

| Tool           | Purpose                                |
|----------------|----------------------------------------|
| **OpenCV**     | Video capture and image processing     |
| **MediaPipe**  | Hand landmark detection                |
| **NumPy**      | Mathematical computation               |
| **PyAutoGUI**  | Simulate mouse and keyboard events     |

## Use Cases

- Accessible control for people with motor impairments  
- Touchless interfaces for kiosks and digital displays  
- Control in sterile or non-contact-required environments  
- Experimental interaction design and learning projects

## 📦 Getting Started

### Prerequisites
- Python 3.7 or higher
- Webcam

### Installation

```bash
git clone https://github.com/amritofficial88/gesture-control.git
cd gesture-control
pip install -r requirements.txt
python main.py
