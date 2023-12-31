# Smile_Capture_Using_OpenCV
Driver Drowsiness Detection: A Python project using facial landmarks and mouth aspect ratio (MAR) to detect driver drowsiness in real-time. Utilizes dlib library for face detection. Analyzes video frames to determine drowsiness and triggers alerts if needed.
# Driver Drowsiness Detection using Python

This project detects driver drowsiness using facial landmarks and mouth aspect ratio (MAR). It utilizes the `dlib` library for face detection and facial landmark prediction. The project captures video frames from a camera feed and analyzes the mouth aspect ratio to determine if the driver is drowsy.

## Prerequisites

- Python 3.7 or above
- OpenCV
- dlib
- imutils
- numpy
- scipy

## Installation

1. Clone the repository:
2. Install the required dependencies:
opencv-python
dlib
imutils
numpy
scipy


## Usage

1. Make sure your camera is connected and accessible.
2. Make sure you have downloaded the "shape_predictor_68_face_landmarks.dat" and saved it on the same directory as the python script. Here is the link to download the file - https://www.kaggle.com/datasets/sergiovirahonda/shape-predictor-68-face-landmarksdat
3. Run the `drowsiness_detection.py` file:
4. The script will start capturing frames from the camera and analyze the mouth aspect ratio to detect drowsiness.
5. Press 'q' to exit the program.

## References

- [dlib](https://github.com/davisking/dlib)
- [imutils](https://github.com/jrosebr1/imutils)
- [OpenCV](https://opencv.org/)

