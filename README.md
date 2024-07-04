# Air-Canvas

This project implements a hand gesture controlled paint application using OpenCV and MediaPipe. It allows users to draw on a canvas by tracking hand gestures captured through a webcam.

## Table of Contents
- [Introduction](#introduction)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [How it Works](#how-it-works)
- [Demo](#demo)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Introduction

Hand Gesture Controlled Paint is an interactive application where users can draw using hand gestures captured by a webcam. It detects key hand landmarks and interprets gestures to control drawing operations on a digital canvas.

## Features

- Real-time hand gesture detection and tracking
- Multiple color selection and drawing options
- Clear canvas functionality
- Interactive user interface with color selection buttons

## Requirements

- Python 3.7+
- OpenCV
- NumPy
- Mediapipe

## Installation

1. Clone the repository:
```
git clone https://github.com/your-username/hand-gesture-paint.git
cd hand-gesture-paint
```
2. Install the required dependencies:
```
pip install opencv-python numpy mediapipe
```


## Usage

1. Run the main script:
```
python air_canvas_ml.py
```

2. Use your hand gestures to draw on the canvas:
- Hold your hand in front of the webcam.
- Use your index finger to draw by moving it on the screen.
- Switch between colors by selecting the color buttons on the interface.
- Clear the canvas by pressing the "CLEAR" button.

## How it Works

The application works by:
- Initializing a virtual canvas using OpenCV.
- Capturing frames from the webcam and detecting hand landmarks using Mediapipe.
- Interpreting hand gestures to draw lines on the canvas based on the movement of the index finger.
- Providing options to switch colors and clear the canvas through interactive buttons.

## Future Improvements

- Enhance gesture recognition accuracy and robustness.
- Implement additional drawing tools such as brush size adjustment.
- Add support for saving and loading drawings.
- Improve user interface design for better usability.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


