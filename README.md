# 🎯 OpenCV-Based Multi-Feature Vision System

A Python-based computer vision application that combines multiple real-time vision features into a single desktop application using OpenCV, MediaPipe, YOLOv8, and Tkinter.

## Features

- ✋ Hand Gesture Volume Control using MediaPipe
- 🎯 Real-Time Object Detection using YOLOv8
- 🎨 Air Drawing using Hand Tracking
- 🖥️ Simple Tkinter-based GUI

## Technologies Used

- Python
- OpenCV
- MediaPipe
- YOLOv8 (Ultralytics)
- NumPy
- Pillow
- PyCAW
- Tkinter

## Installation

Clone the repository:

```bash
git clone https://github.com/ronak3504/OpenCV-Based-Multi-Feature-Vision-system.git
cd OpenCV-Based-Multi-Feature-Vision-system
```

Create a virtual environment:

```bash
python -m venv .venv
```

Activate the virtual environment:

### Windows

```bash
.venv\Scripts\activate
```

### Linux/macOS

```bash
source .venv/bin/activate
```

Install the required packages:

```bash
pip install -r requirements.txt
```

Run the application:

```bash
python main.py
```

## Project Structure

```
├── main.py
├── our project bgm.jpg
├── README.md
├── .gitignore
└── requirements.txt
```

## Note

The YOLOv8 model (`yolov8n.pt`) is downloaded automatically by Ultralytics during the first run if it is not already available.

## Author

**Ronak Soni**

GitHub: https://github.com/ronak3504
