# Hand Tracking with CVZone

This project demonstrates hand tracking using the HandTrackingModule from CVZone. It allows you to track the movements of your hands in real-time using your webcam.

## Features
- Detects and tracks the positions of both hands simultaneously.
- Calculates the distance between the center points of both hands.
- Displays the distance between hands on the video feed.
- Draws a stretching line between the index fingers of both hands.

## Requirements
- Python 3.x
- OpenCV
- CVZone library

## Installation
1. Clone the repository:
   ```
   git clone https://github.com/yourusername/hand-tracking-cvzone.git
   ```
2. Install the required packages:
   ```
   pip install opencv-python
   pip install cvzone
   ```

## Usage
1. Run the `hand_tracking.py` script:
   ```
   python hand_tracking.py
   ```
2. The webcam will open, and you will see the live video feed with hand tracking and stretching line visualization.
3. Press 'q' to exit the application.

## Future Improvements
- Implement gesture recognition for performing actions based on hand gestures.
- Add support for more complex hand interactions and gestures.
- Integrate with other computer vision algorithms for more advanced applications.

## Acknowledgments
This project utilizes the HandTrackingModule from the CVZone library, developed by [Murtaza's Workshop - Robotics and AI](https://github.com/murtazahassan).

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
