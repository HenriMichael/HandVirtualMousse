# HandVirtualMousse
This project creates a virtual mouse controller using hand tracking with your webcam. By detecting hand movements, it allows you to move the mouse cursor and perform clicks with gestures.

## Features

- **Real-time hand tracking** using MediaPipe.
- **Control mouse cursor** with your index finger.
- **Click functionality** by bringing your thumb and index finger together.
- **Cross-platform compatibility** (Windows, macOS, Linux).

## Requirements

Make sure you have the following libraries installed:

- Python 3.x
- OpenCV
- MediaPipe
- PyAutoGUI

You can install the required libraries using pip:

pip install opencv-python mediapipe pyautogui

## Usage
**Clone the repository**:
git clone https://github.com/HenriMichael/HandVirtualMousse.git
cd HandVirtualMousse

**Run the script**:
python main.py

**Use the virtual mouse**:
Move your index finger to control the cursor.
Bring your thumb close to your index finger to perform a click.

## Controls
Index Finger: Move the mouse cursor.
Thumb and Index Finger Together: Click the mouse.

## Notes
Ensure that your environment is well-lit for optimal hand detection.
Position your webcam so that your hands are clearly visible.
Adjust the threshold for clicking based on your preference.

## Troubleshooting
No Hand Detection: Ensure your hands are visible to the camera and that the lighting is adequate.
Clicking Issues: You may need to adjust the distance threshold in the code for better accuracy.

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Acknowledgments
OpenCV for computer vision.
MediaPipe for hand tracking solutions.
PyAutoGUI for automation.
