Invisibility Cloak (Python OpenCV)

A real-time invisibility cloak effect using Python and OpenCV.
The program detects a specific cloth color and replaces it with the captured background to create a disappearing effect.

Features

Real-time cloak detection

Smooth, stable background blending

Supports green cloak (best performance)

Efficient, low-lag processing

Works with any webcam

How It Works

The camera captures a background image with no person in the frame.

The script identifies the cloak color in HSV.

Masked regions are replaced by the background image.

The result makes the cloak area appear invisible.

Tech Used

Python

OpenCV

NumPy

How to Run
python green_cloak.py


Controls:

b capture background

q quit

Folder Structure
Invisibility-Cloak/
    src/
        green_cloak.py
    demo/
        demo.mp4
    README.md

Demo Video

(Upload your demo.mp4 to the demo folder)

Author

Manisankar
AI & DS Engineer
