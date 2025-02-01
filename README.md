### Gesture Recognition System

# Overview

The Gesture Recognition System is a technology-driven solution that interprets and analyzes human gestures captured through cameras. Leveraging TensorFlow, MediaPipe, and OpenCV, this system enables accurate and real-time recognition of hand movements and poses.

# Technologies Used

- TensorFlow: Empowers the development of deep learning models for gesture classification.

- MediaPipe: Facilitates precise hand tracking and pose estimation, enhancing spatial orientation understanding.

- OpenCV: Performs image processing and computer vision tasks as well as some math required for certain gestures. Also responsible for image output.

# Usage

See ARmedHGR to learn in detail how each method works

Otherwise, tfod contains all neccessary and important files, including many key functions, the machine learning framework, and the main file.
App.py is the program that will be run on the glasses themselves. App.py uses every other file to:

1. Identify Gestures

The gestures app.py is able to recognize currently is:

- Zoom
- Left Hand and Right Hand Point

2. Calculate necessary values associated with the gestures

Right now the values app.py is calculating is:

- Distance between pinched hands - Zoom
- Coordinate points for the tip of the index finger of both hands - Left Hand and Right Hand Point

\

To start using the project:

1. Run C Sharp Server

Change directory to "TCP testing\TCP"
In your terminal type in "dotnet run"
When you see "Server listening on port 12345 Connection from 127.0.0.1", the server is running properly.

2. Run main file

Change directory to C:\Users\Aadi\Desktop\ARmed\ARmedEngineering\tfod"
In your terminal type in "py app.py"
A new window should open accessing your camera. From there you can start making gestures.


# Installation

Install pip

- In command prompt type in "curl https://bootstrap.pypa.io/get-pip.py -o get-pip.py"
After that type in "python get-pip.py"

Install Mediapipe

- In command prompt type in "pip install mediapipe"

Install OpenCV

- In command prompt type in "pip install opencv-python"

Install Tensorflow

- In command prompt type in "pip install tensorflow"


