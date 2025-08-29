#face_detection
face_detection_with_face
Face, Eye, and Mouth Detection Using OpenCV
🎯 Objective
This project uses OpenCV's Haar Cascade Classifiers to detect human faces, eyes, and mouths in real-time using a webcam. It demonstrates how to apply object detection with pre-trained models on live video streams.

🧠 Techniques Used
Haar Cascade Classifier (Pre-trained XML files)

Real-time video processing using OpenCV

ROI (Region of Interest) for feature detection

Annotation on video frames (bounding boxes & text)

🧼 Data Cleaning
No external dataset is used. The live video feed is captured directly from the webcam and converted into grayscale before detection.

📊 Data Visualization
Real-time bounding boxes around faces, eyes, and mouths

Labeled detections displayed directly on video frames

🤖 Algorithms Used
Haar Cascade Classifier for:

Face detection

Eye detection

Mouth (smile) detection

✅ Model Evaluation Methods Used
Visual inspection of detections

Real-time performance observation (frame rate, detection accuracy)

🛠️ Packages and Tools Required
OpenCV (cv2)

Jupyter Notebook or any Python IDE (for testing)

📦 Installation Instructions
pip install opencv-python
If you're using Jupyter Notebook, install it from the official guide:
📘 Jupyter Installation Guide

📸 How It Works
Load Haar cascades for face, eye, and mouth detection.

Capture video from the default webcam.

Convert each frame to grayscale for better processing.

Detect faces and then detect eyes and mouths within each face region.

Display the video stream with bounding boxes and labels.

Press 'q' to quit.

📂 Project Structure (Recommended)
face-eye-mouth-detection/
│
├── haarcascade_frontalface_default.xml
├── haarcascade_eye.xml
├── haarcascade_smile.xml
├── face_eye_mouth_detection.py
├── README.md
📝 Guide Lines
Ensure good lighting conditions for better accuracy.

Use high-resolution webcam for better face detection.

Adjust scaleFactor and minNeighbors if detection is unstable.

