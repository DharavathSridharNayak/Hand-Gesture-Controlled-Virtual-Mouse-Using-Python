# 🖐️ HAND GESTURE CONTROLLED VIRTUAL MOUSE USING PYTHON 🖥️🖱️

Control your computer mouse cursor using hand gestures with the power of Computer Vision and Python. This project leverages your webcam to track hand landmarks in real-time and enables gesture-based control of mouse movement and clicks — without touching a physical mouse.
----------------------------------------------------------------
🚀 Features:

🖐️ Real-time hand tracking using MediaPipe

🎯 Cursor movement using index finger

👆 Left click with index & middle finger gesture

✌️ Right click with custom hand gesture

🎥 Webcam-based input

🧠 Smart gesture smoothing for stable cursor control

----------------------------------------------------------------

🛠️ Technologies Used:

Python 🐍

OpenCV 📷

MediaPipe 🧠

PyAutoGUI 🖱️

NumPy 🔢

-------------------------------------------------------------------------------

📁 Project Structure
bash
Copy
Edit
📦 HandGesture-Virtual-Mouse/
├── Hand Gesture .ipynb         # Colab notebook
├── requirements.txt            # Python dependencies
├── README.md                   # Project overview
├── How to run.txt              # It shows how it works
 └── screenshots/            # Images to show in README or repo
    -------------------------------------------------------------------------------

📸 How It Works: 

Uses MediaPipe to detect 21 hand landmarks

Maps the index finger position to screen coordinates

Detects gestures:

Index Finger Only → Move Cursor

Index + Middle Finger Together → Left Click

Three Fingers (optional) → Right Click

--------------------------------------------------------------
📝 Requirements: 
Python 3.7+

OpenCV

MediaPipe

PyAutoGUI

NumPy


📸 Screenshot 👇👇

![{2B0433E2-DA37-4F43-BE2D-D4021D40A59B}](https://github.com/user-attachments/assets/d93f3602-064f-4a96-9d9e-f74fa838c400)


