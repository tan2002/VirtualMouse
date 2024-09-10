# Virtual Mouse Using Hand Gestures

## Overview

**Virtual Mouse** is a project that allows users to control the mouse cursor using hand gestures. It leverages computer vision and machine learning techniques to recognize hand movements and map them to mouse actions, offering a novel way to interact with your computer.

## Features

- **Gesture Control**: Use hand gestures to move the mouse cursor, click, scroll, and drag.
- **Real-Time Detection**: Employs OpenCV and Mediapipe for real-time hand detection and gesture recognition.
- **Calibration Mode**: Includes a calibration mode to adapt to different hand sizes and lighting conditions.
- **Low Latency**: Optimized for accurate and responsive cursor movements.

## Technologies Used

- **Python**: Programming language used for development.
- **OpenCV**: Library used for real-time computer vision tasks.
- **PyAutoGUI**: Library used for simulating mouse actions.
- **Mediapipe**: Framework for hand gesture recognition.

## Installation

1. **Clone the Repository**: `git clone https://github.com/tan2002/virtual-mouse.git`
2. **Navigate to the Project Directory**: `cd virtual-mouse`
3. **Install Dependencies**: Make sure you have Python installed. Then install the required libraries using pip: `pip install opencv-python pyautogui mediapipe`

## How to Run

1. **Run the Application**: `python main.py`

## Usage Instructions

- **Calibration**: Follow the on-screen instructions to calibrate the system for your hand size and lighting conditions.
- **Control**: Use hand gestures to move the cursor and perform actions like clicking and scrolling.

## Contributing

Feel free to fork the repository and submit pull requests. For any issues or feature requests, please open an issue in the repository.

## License

This project is licensed under the **GNU General Public License v3.0 (GPL-3.0)** - see the [LICENSE](LICENSE) file for details.
