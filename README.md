# Face Gesture Control with OpenCV and MediaPipe

This project uses OpenCV and MediaPipe to track facial landmarks and control the mouse pointer using face gestures. Specifically, it tracks the eye and mouth regions of the face and moves the cursor based on these movements. Additionally, it includes a click action based on the mouth gesture.

## Features

- **Face Mesh Detection**: Uses MediaPipe's Face Mesh to detect and track facial landmarks in real time.
- **Mouse Cursor Control**: Moves the cursor on the screen based on the position of specific facial landmarks.
- **Click Gesture**: Detects a specific mouth gesture (a slight difference in the vertical distance between two landmarks) to simulate a mouse click.
- **Real-time Performance**: Achieves smooth real-time performance with a webcam.

## Requirements

- Python 3.x
- Libraries:
  - `opencv-python`
  - `mediapipe`
  - `pyautogui`

You can install the required libraries using pip:

```bash
pip install opencv-python mediapipe pyautogui
