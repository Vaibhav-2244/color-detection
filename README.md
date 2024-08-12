# Color Detection
=====================

A Python program that detects and tracks colors in real-time using OpenCV.

### Features

* Detects and tracks blue, yellow, green, red, and orange colors
* Uses HSV color space for accurate color detection
* Applies adaptive thresholding and morphological operations to reduce noise
* Displays detected colors with bounding boxes and labels

### Usage

1. Clone the repository: `git clone https://github.com/Vaibhav-2244/color-detection.git`
2. Install the required packages: `pip install -r requirements.txt`
3. Run the program: `python main.py`

### How it Works

The program uses the OpenCV library to capture video from the default camera. It then converts each frame to the HSV color space and applies color detection using the `get_limits` function from the `util.py` file. The detected colors are then tracked and displayed with bounding boxes and labels.

### Configuration

You can adjust the color detection limits by modifying the `get_limits` function in the `util.py` file. The function returns the lower and upper limits for each color in HSV format.

