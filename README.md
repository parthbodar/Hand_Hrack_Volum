# Volume Control with Hand Gestures

This project uses computer vision and hand tracking to control the system volume using hand gestures. The hand gestures are captured using a webcam, processed with `MediaPipe`, and used to simulate keypress events for controlling volume.

## Files
- **`VolumeHandControl.py`**: Basic volume control, detects hand gestures to decrease the volume.
- **`VolumeHandControlAdvance.py`**: Advanced volume control, includes logic for more complex hand gestures to increase/decrease volume.
- **`HandTrackingModule.py`**: Contains the logic for detecting hands using `MediaPipe` and tracking hand landmarks.

## Requirements
- Python 3.x
- Install the required dependencies by running the following command:
    ```bash
    pip install opencv-python pyautogui mediapipe numpy
    ```

## Usage
1. Clone or download the repository.
2. Run the `VolumeHandControl.py` or `VolumeHandControlAdvance.py` file.
3. Use your hand gestures to control the system volume.

## Download
You can download the project files from the following link:
[Download Project Files](https://your-download-link.com)

## License
This project is open-source and free to use.
