# FingerCounter

FingerCounter is a project that utilizes the Mediapipe library and a camera to detect a hand and count the raised fingers. 
The project is written in Python.

# How it works

The project uses the OpenCV library to capture video frames from the camera. <br>
It leverages the Mediapipe library to process the captured frames and detect hand landmarks. <br>
The hand landmarks are analyzed to determine the position and status of each finger. <br>
Based on the finger positions, the FingerCounter algorithm counts the raised fingers.
The counted fingers are displayed on the video frame as well as the FPS (Frames Per Second) counter in the bottom left corner. <br>
The process continues in real-time, providing a continuous count of the raised fingers. <br>

# Getting Started

To run the FingerCounter project, follow these steps:

Clone the project repository from GitHub: git clone https://github.com/Argones/FingerCounter.git <br>
Install the required dependencies using pip: pip install -r requirements.txt <br>
Connect a camera or webcam to your system. <br> 
Run the main script: python finger_counter.py <br>
The camera feed will open, and you can start raising your fingers to see the count and FPS displayed on the screen. <br>

# End

Feel free to explore and modify the code to suit your needs. Happy finger counting!
