# Deep-Learning-based-Eye-Driven-Mouse-Cursor
This project implements a hands-free mouse cursor control system using deep learning and computer vision techniques. The application leverages facial landmarks to detect eye and mouth movements, enabling intuitive control of the mouse pointer, clicks, and scrolling actions.

**Features**
Eye Blinks: Perform left and right mouse clicks.
Mouth Movements: Activate or deactivate input mode for cursor control.
Nose Tracking: Use the nose position to move the cursor across the screen.
Scroll Mode: Enable or disable vertical scrolling using eye blinks.

**Prerequisites**
Ensure you have the following installed:
Python 3.8+

**Required libraries:**
numpy
opencv-python
imutils
pyautogui
dlib
Additionally, you will need the shape_predictor_68_face_landmarks.dat file for detecting facial landmarks.

**Usage**
_Mouse Control:_
Move your head to guide the cursor using your nose position.
Perform left/right eye blinks to simulate left/right mouse clicks.
_Scroll Mode:_
Activate scroll mode with a double-eye blink.
Use head movements (up/down) to scroll.
_Input Mode:_
Open your mouth wide to toggle input mode for precise cursor movement.

**Code Overview**
The application uses Dlib's pre-trained facial landmark detector to identify key facial regions:
Eyes: Calculating the Eye Aspect Ratio (EAR) to detect blinks.
Mouth: Calculating the Mouth Aspect Ratio (MAR) to detect wide openings.
Nose: Tracking the nose tip for cursor movement.

**Contribution**
Feel free to fork this repository and submit pull requests to enhance functionality or fix issues.
