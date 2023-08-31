# Real-Time Canny Edge Detection with OpenCV

This is a simple Python script that uses the OpenCV library to perform real-time edge detection using the Canny edge detection algorithm on the video feed from your computer's webcam.

## Requirements

- Python 3.x
- OpenCV library (`opencv-python`)

## Installation

1. Make sure you have Python 3.x installed on your system.
2. Install the OpenCV library using the following command:

## Usage

1. Clone or download this repository to your local machine.
2. Navigate to the project directory.
3. Run the script using the following command:
4. A window will pop up showing the real-time webcam feed with Canny edge detection applied. Press the "Esc" key to exit the program.

## Explanation

The script performs the following steps:

1. Imports the OpenCV library.
2. Initializes the webcam capture.
3. Enters a loop to continuously capture frames and process them.
4. Applies Canny edge detection to each frame.
5. Displays the edge-detected frames in a window.
6. Waits for the "Esc" key to be pressed to exit the program.

## Customization

You can customize the Canny edge detection by modifying the `threshold1` and `threshold2` parameters in the script. Adjusting these values will affect the sensitivity of edge detection.

## Contribution

Feel free to contribute to this project by submitting pull requests. If you have suggestions or improvements, please open an issue to discuss them.
