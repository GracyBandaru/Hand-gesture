# Hand Gesture Recognition with Mediapipe

## Description
This Python script utilizes OpenCV and Mediapipe to detect hand gestures in real time using a webcam. It tracks hand landmarks, calculates finger positions, and determines the number of fingers raised. The project is ideal for interactive applications or gesture-based user interfaces.

## Features
- Real-time hand landmark detection using Mediapipe.
- Gesture recognition to count the number of fingers raised.
- Displays the frame rate (FPS) for performance monitoring.
- Supports tracking of up to two hands simultaneously.

## Tech Stack
- Python
- OpenCV
- Mediapipe

## Usage

### 1. Install Dependencies
Ensure you have Python installed. Then, install the required libraries:
```bash
pip install opencv-python mediapipe
```

### 2. Run the Script
Execute the script using:
```bash
python hands_2.py
```

### 3. Interact with the Webcam
- Raise your hand in front of the webcam to see the landmarks and finger count.
- Press `q` to exit the application.

## Example
- Displays the number of fingers raised on the screen.
- Tracks hand gestures in real time with visualizations of landmarks.
