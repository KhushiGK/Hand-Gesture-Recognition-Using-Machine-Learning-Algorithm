# Hand-Gesture-Recognition-Using-Machine-Learning-Algorithm
The python code 'handDetectorModule' takes the webcam video (series of images) from the system as an input. The code will check if there are any hands in the input images taken by the camera. If yes, then the module will draw landmarks on the hand based on the mediapipe hand module. Then the image is returned with the landmarks drawn. A list is created which will take all the positions of the landmarks of the hand and return that list.

In the python code 'gestureMediaController' we have imported pyautogui for keyboard and mouse controls. We have also imported a pycaw library for audio control. We have created our own gestures using the mediapipe framework image output given by the 'handDetectorModule'. The fingertips help in the gesture recognition. The results obtained at the end include:
1. The distance between the index finger and the thumb implements the volume controls(Increase/Decrease).
2. If the thumb is folded:
    all the other four fingers are folded, then the media will pause or play.
3. If three fingers are folded and the little finger is open, then the media will go five seconds forward.
4. If three fingers are folded and the index finger is open, then the media will go five seconds backwards.

Hand gesture detection for media control is an innovative use of machine learning. Hand motions taken by a camera are detected, analyzed, and then used to control different media playback functions like volume, play/pause, forward, and rewind.
There are many benefits to using gesture recognition for media control. It provides a touchless and hands-free solution, for example, making it a convenient and user-friendly choice. It can also be useful when both hands are busy if there is no direct access to media playback controls.

The application of machine learning techniques, especially image processing and computer vision techniques, is required for the implementation of this technology. These algorithms are useful for real-time tracking the user's hand and position,and then mapping the hand's movement to a specific media control.

The MediaPipe framework, which provides a pre-trained model for hand detection and tracking, is a popular tool for hand gesture recognition. With a set of hand gesture images, this model can be fine-tuned to recognize particular gestures and map them to media control functions.


<img width="462" alt="image" src="https://github.com/KhushiGK/Hand-Gesture-Recognition-Using-Machine-Learning-Algorithm/assets/82925917/1212f81c-106d-4c33-99e7-db8f6dc28812">
