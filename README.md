🎭 Real-Time Emotion Detection System
A real-time facial emotion detection system that identifies and classifies
human emotions from a live webcam feed using deep learning and computer vision.

📌 About The Project
This project captures live video from a webcam, detects faces in each frame,
and classifies the emotion being expressed. It can detect 7 emotions in real
time and displays the result directly on the video feed.

✨ Features

🎥 Real-time webcam face detection
😊 Detects 7 emotions — Happy, Sad, Angry, Neutral, Surprise, Fear, Disgust
🖼️ Draws bounding box around detected face with emotion label
⚡ Fast and lightweight using DeepFace library


🛠️ Technologies Used
:PythonCore programming language,
OpenCVWebcam capture & face detection,
DeepFaceEmotion classification model,
Haar CascadeFace detection classifier,

⚙️ How To Run
Step 1 — Install required libraries:
bashpip install opencv-python deepface
Step 2 — Run the project:
bashpython emotion-detection.py
Step 3 — Allow webcam access when prompted
A window will open showing your live webcam feed with emotion labels displayed in real time.
Press Q to quit.

📁 Project Structure
emotion-detection/
└── emotion-detection.py    # Main script

📸 How It Works

OpenCV captures live video from your webcam frame by frame
Haar Cascade classifier detects the face region in each frame
DeepFace model analyzes the face and predicts the emotion
The emotion label is drawn on screen in real time


🎓 About
Developed as part of B.Tech in Computer Science & Engineering
@ MRITS, Hyderabad
Author: Aadhya MP
GitHub: github.com/mpaadhya
