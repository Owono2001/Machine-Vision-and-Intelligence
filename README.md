# Real-Time Hand Gesture Recognition System

This project was developed for the Machine Vision and Intelligence (MVI) course assignment. Our team built a vision-based system capable of detecting and classifying various hand gestures in real-time using advanced machine learning techniques.

## Overview

The primary goal of this project is to create an intuitive interface for human-computer interaction through hand gestures. The system processes video input to accurately identify hand presence, orientation, and specific gestures like finger counting and swiping motions. We leverage state-of-the-art computer vision and deep learning models to achieve robust performance.

## Key Features

* **Real-Time Processing:** Analyzes video streams to detect and classify gestures instantaneously.
* **Finger Count Detection:** Accurately counts the number of fingers extended (e.g., 1, 2, 3, 4, 5).
* **Swipe Gesture Recognition:** Detects directional swiping motions (e.g., left, right, up, down - *confirm directions if applicable*).
* **Hand Orientation Classification:** Differentiates between:
    * Left vs. Right Hand
    * Palm vs. Back of Hand
* **Object Detection:** Utilizes YOLOv8 for robust hand detection within the video frame.
* **Gesture Classification:** Employs Convolutional Neural Networks (CNNs) for accurate classification of detected hand gestures.

## Technologies Used

* **Programming Language:** Python
* **Computer Vision:** OpenCV (for image preprocessing, video stream handling)
* **Object Detection:** YOLOv8
* **Deep Learning / Classification:** Convolutional Neural Networks (CNNs) - (*Specify framework if possible, e.g., TensorFlow, PyTorch*)

## System Architecture (Conceptual)

1.  **Video Input:** Capture video stream from a camera source.
2.  **Image Preprocessing:** Use OpenCV for frame resizing, color conversion, and normalization.
3.  **Hand Detection:** Apply the YOLOv8 model to detect the location (bounding box) of hands in the frame.
4.  **Region of Interest (ROI) Extraction:** Crop the detected hand region for focused analysis.
5.  **Gesture Classification:** Feed the cropped hand image into the trained CNN model to classify the gesture (finger count, swipe, orientation).
6.  **Output:** Display the recognized gesture information on the video feed or output it for further application use.

## Team Members

* Shokri Eyad Shokri Ouda (TP065881)
* Aravind Soundirarajan (TP066273)
* Pedro Fabian Owono Ondo Mangue (TP063251)

---
