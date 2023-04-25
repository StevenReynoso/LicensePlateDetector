# LicensePlateDetector
License Plate detection using c++ and openCV

License Plate Detection with OpenCV

This is a C++ project that uses the OpenCV library to detect license plates in real-time video captured by a webcam or other camera device. The project includes a pre-trained CascadeClassifier object that contains a Haar-like feature-based classifier to detect license plates in the captured images.
Getting Started
Prerequisites

To run this project, you need to have OpenCV installed on your system. You can download and install OpenCV from the official website: https://opencv.org/releases/
Installation

    Open the project in your preferred C++ IDE (such as Visual Studio or Code::Blocks).
    Build the project and run the executable file.

Usage

When you run the program, it will open a window showing the live video captured by your camera device. The program will detect license plates in the video frames and draw a rectangle around each detected license plate. It will also display each detected license plate in a separate window and save it as a PNG file in the "Resources/Plates/" directory.

To stop the program, press the "ESC" key or close the program window.
