# Virtual-Mouse-using-Eye-tracking

This project implements an eye-controlled mouse using OpenCV, MediaPipe, and PyAutoGUI. The system tracks eye movement to control the cursor and detects blinks to perform click actions.

Features
Cursor Control: Moves the cursor based on eye movement.
Single Blink: Left-clicks the mouse.
Double Blink: Right-clicks the mouse.
Triple Blink: Opens the Start menu.
Scrolling: Moves the page up or down based on eye gaze direction.

Requirements
Python 3.x
OpenCV (cv2)
MediaPipe
PyAutoGUI

How It Works
Eye Tracking: Uses MediaPipe FaceMesh to detect landmarks around the eyes.
Blink Detection: Measures the vertical distance between eyelid landmarks.
Cursor Movement: Maps eye position to screen coordinates.
Scrolling: Detects upward and downward gaze to scroll accordingly.
