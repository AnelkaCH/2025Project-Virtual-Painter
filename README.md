# Hand Landmark Detection & Virtual Drawing 🎨

(Note: This project was made in 2025, but I decided to upload it to GitHub in 2026 to keep it safe :D. )

A real-time hand tracking program using MediaPipe that detects 21 hand landmark points and uses their positions to create a virtual drawing application, drawing on screen by moving your index finger.

## Overview

The program uses MediaPipe's hand tracking solution to detect and track 21 anatomical landmarks on a hand in each webcam frame. A custom `HandTrackingModule` class wraps the MediaPipe API. By tracking the position of the index fingertip landmark over time, the program enables drawing colored lines on a virtual canvas overlaid on the webcam feed.

## Concepts Learned

- MediaPipe library and its hand landmark model
- 21 hand landmark node structure and anatomical naming
- Wrapping a library into a reusable class module
- Real-time landmark position extraction with `findPosition()`
- Drawing mode vs selection mode logic
- Overlaying a canvas on live video frames

## Demo

https://github.com/user-attachments/assets/6d5a3c1d-6240-4660-baae-a453885e69c5


## Setup

```
pip install mediapipe opencv-python numpy
```
