# Hand-Controlled-Video-Media-Player
This project enables a hand gesture-based control system using OpenCV, MediaPipe, and PyAutoGUI. The system detects hand gestures from a webcam feed and simulates corresponding keyboard presses, allowing you to interact with your computer using hand gestures in real-time. It recognizes five specific gestures (one to five fingers)

pip install opencv-python mediapipe pyautogui

The project captures hand gestures using the webcam and processes the video frames to detect finger movements. Depending on the number of fingers detected, specific keyboard actions are triggered using PyAutoGUI. The following gestures are mapped to keyboard keys:

1 finger: Right Arrow Key (Move Right)
2 fingers: Left Arrow Key (Move Left)
3 fingers: Up Arrow Key (Move Up)
4 fingers: Down Arrow Key (Move Down)
5 fingers: Space Bar (Press Space)
