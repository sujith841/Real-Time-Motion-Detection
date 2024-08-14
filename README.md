# Real-Time Motion Detection and Alert System

Welcome to the Real-Time Motion Detection and Alert System repository! This project utilizes AI and computer vision techniques to monitor a live camera feed, detect motion, and trigger an audible alert when movement is detected.

## 🚀 Project Overview

This project leverages **OpenCV** to process video frames in real-time, detect motion, and generate alerts. It’s designed to be lightweight and efficient, capable of running on standard hardware with minimal latency.

### Key Features

- **Real-Time Motion Detection**: Detects movement in live video feeds using advanced image processing techniques.
- **Thresholding & Blurring**: Uses Gaussian Blur and binary thresholding to enhance detection accuracy.
- **Multi-threaded Alarm System**: The alert system runs on a separate thread to ensure it doesn't interfere with the main video processing.
- **User Control**: Easily toggle the alarm mode and exit the program with simple key presses.

## 🛠️ Installation

To get started with the project, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/yourusername/motion-detection-alert-system.git
cd motion-detection-alert-system
pip install -r requirements.txt
