# OpenCV_Virtual_Mouse_
An AI based Python program that allows user to virtually control their mouse using hand movements.The program uses a real-time camera that detects hand landmarks, tracks gesture patterns instead of a physical mouse.

# Dependencies
Please install all the required dependencies.

Languages:
Python (I recommend Python 3.7, as it makes installing autopy easier. However, if you area able to install it on a more recent python version, then go ahead)

Libraries/packages:
- openCV - For camera feed, image processing, and drawing
- mediapipe - Employs machine learning to infer 3D landmarks of the - hand from single frames in real-time without any fancy hardware acceleration. Used for hand tracking in the program
- autopy - For controlling the mouse movement and click
- numpy - For working with arrays

# Installation
To setup the system for development on your local machine, please follow the instructions below:

Clone the repository to your machine

git clone https://github.com/Tochi-Onwuasoanya/OpenCV_Virtual_Mouse.git

Run the virtualmouse.py python file.

# How to Use
- Use pointer finger to move cursor
- Close point finger and have thumb extended in order to click (left click)
- **[View the Demo;]([https://codepen.io/tochi2310/pen/poVdExZ](https://drive.google.com/file/d/1fLIwELAQYQB2JngZqpHKeaHs7rFX5NtA/view?usp=sharing))**

# Next steps
- Drag and drop functions
- Right click
- Toggle
