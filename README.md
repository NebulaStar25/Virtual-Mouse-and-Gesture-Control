# Virtual Mouse & Gesture Control
This project implements a virtual mouse using computer vision and hand gesture recognition. It allows you to control your computer mouse, perform clicks, scrolling, adjust system volume, and even change screen brightness — all using hand gestures captured by a webcam.

Built with Python, OpenCV, MediaPipe, and PyAutoGUI, this project demonstrates the power of AI and HCI (Human-Computer Interaction) by replacing hardware peripherals with intuitive gesture-based controls.

# Features
- Cursor Movement: Move the mouse cursor using your hand.
- Left Click & Drag: Fist gesture to grab and drag.
- Right Click: Index finger gesture.
- Double Click: Two-finger closed gesture.
- Scrolling: Minor hand pinch → scroll vertically/horizontally.
- Volume Control: Major hand pinch → increase or decrease system volume.
- Brightness Control: Adjust screen brightness with pinch gesture.
- Robust Noise Filtering: Ensures stable gesture detection using frame-based debouncing.

# Tech Stack
Python 3.x
OpenCV — computer vision library
MediaPipe — hand tracking and landmarks
PyAutoGUI — mouse and keyboard automation
PyCAW — system volume control
screen-brightness-control — brightness adjustments

# Usage
Place your hand in front of the webcam. The system will detect landmarks using MediaPipe Hands.
Perform gestures:
# Gesture	                  Action
V-Sign	              Enable cursor control
Fist	                Drag / Hold left mouse button
Index Finger	        Right Click
Closed Fingers	      Double Click
Pinch (Minor hand)	  Scroll up/down/left/right
Pinch (Major hand)	  Adjust volume / brightness
Open Palm	            Neutral (no action)
Press Enter (↵) to exit the program.

# Future Improvements
- Add support for multi-hand interaction (both hands controlling different actions simultaneously).
- Implement gesture customization through configuration.
- Improve accuracy in low-light conditions.
