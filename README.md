# Spatial Touch

This project implements a hand gesture-based mouse control system using computer vision techniques. It allows users to control their computer's mouse cursor and perform clicks using hand gestures captured by a webcam.

## Features

- Move the mouse cursor using your index finger
- Perform mouse clicks by pinching your index finger and thumb
- Real-time hand tracking and gesture recognition
- Adjustable sensitivity and smoothing for precise control

## Requirements

- Python 3.8.0
- OpenCV
- MediaPipe
- NumPy
- Autopy
- PyAutoGUI
- Comtypes
- Pycaw
- Screen Brightness Control

## Installation

1. Clone this repository:
   ```
   git clone https://github.com/your-username/hand-gesture-mouse-control.git
   cd hand-gesture-mouse-control
   ```

2. Create a virtual environment (optional but recommended):
   ```
   python -m venv venv
   source venv/bin/activate  # On Windows, use `venv\Scripts\activate`
   ```

3. Install the required packages:
   ```
   pip install -r requirements.txt
   ```

   Note: Some packages might require additional system dependencies. Please refer to their respective documentation if you encounter any issues during installation.

## Usage

1. Run the main script:
   ```
   python main.py
   ```

2. Position your hand in front of the webcam.

3. Use the following gestures:
   - Move your index finger to control the mouse cursor
   - Pinch your index finger and thumb together to perform a mouse click

4. Press 'q' to quit the application.

## Customization

You can adjust various parameters in the `main.py` file to fine-tune the behavior:

- `wCam` and `hCam`: Camera resolution
- `frameR`: Frame reduction for the active area
- `smoothening`: Smoothing factor for mouse movement

## Troubleshooting

If you encounter any issues:

1. Ensure your webcam is properly connected and accessible.
2. Check that you're using Python 3.8.0.
3. Verify that all required packages are installed correctly.
4. Adjust lighting conditions for better hand detection.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.


## Acknowledgements

- [OpenCV](https://opencv.org/)
- [MediaPipe](https://mediapipe.dev/)
- [Autopy](https://github.com/autopilot-rs/autopy)
