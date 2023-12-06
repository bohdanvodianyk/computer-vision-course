# Real-Time Hand Tracking

This repository contains a Python-based hand tracking project that utilizes the capabilities of the MediaPipe library and OpenCV to detect and track hand landmarks in real-time video feeds.

## Project Structure

- **HandTrackingModule.py**: This script defines a `handDetector` class that encapsulates the functionality needed to detect hands and their landmarks using MediaPipe. It offers methods for finding hands in images and determining the positions of hand landmarks.
- **HandTracking.py**: This script uses the `handDetector` class to perform real-time hand tracking. It captures video from a webcam, processes the frames to find hand landmarks, and displays the results in a real-time video stream.

## Features

- **Real-Time Hand Detection**: Detects hands in real-time using a webcam.
- **Landmark Tracking**: Identifies and tracks key landmarks of a hand, such as fingertips and joints.

## Getting Started

### Prerequisites

- Python 3.x
- OpenCV
- MediaPipe

### Installation

1. Clone the repository.
2. Install required libraries:
   pip install opencv-python mediapipe


### Usage

Run the `HandTracking.py` script to start the hand tracking application:

python HandTracking.py

## Acknowledgements

- This project uses the [MediaPipe](https://google.github.io/mediapipe/) framework for hand tracking.
