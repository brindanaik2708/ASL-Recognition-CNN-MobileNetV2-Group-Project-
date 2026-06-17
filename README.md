# ASL Recognition — CNN + MobileNetV2 (Group Project)

Real-time American Sign Language (ASL) Recognition system that converts hand gestures (A–Z) into text and speech using Deep Learning, MobileNetV2, MediaPipe, and OpenCV.

## Project Overview

This project was developed as a group academic project for the Computer Engineering program (2024–25). The goal was to build a practical assistive system that helps bridge communication barriers by recognizing ASL hand gestures in real time and converting them into readable and spoken output.

The system captures hand gestures through a webcam, identifies the corresponding ASL alphabet, builds words letter by letter, and provides text-to-speech output.

## Team Members

* Brinda Naik
* Moksha Patel
* Nyasa Desai
* Arya Patel
* Manya Jain

## My Contributions

* Participated in project design and development.
* Assisted with dataset preparation and preprocessing.
* Contributed to model training, testing, and evaluation.
* Worked on project documentation and result analysis.
* Collaborated on debugging and system integration.

> Note: This was a collaborative team project. All major components were developed jointly by the project team.

## Key Features

* Real-time ASL alphabet recognition (A–Z)
* MobileNetV2-based transfer learning model
* MediaPipe hand landmark detection
* Live webcam inference
* Word formation from detected letters
* Text-to-speech output
* Confidence-based prediction visualization
* Real-time performance with low latency

## Results

| Metric              | Value    |
| ------------------- | -------- |
| Training Accuracy   | ~99%     |
| Validation Accuracy | ~94%     |
| Classes             | 26 (A–Z) |
| Frame Rate          | ~30 FPS  |
| Latency             | <200 ms  |

## Technologies Used

* TensorFlow
* Keras
* MobileNetV2
* OpenCV
* MediaPipe
* NumPy
* Matplotlib
* pyttsx3

## Skills Demonstrated

* Deep Learning
* Transfer Learning
* Computer Vision
* Image Classification
* Model Evaluation
* Real-Time Inference
* Team Collaboration
* Software Documentation

## Future Improvements

* Dynamic gesture recognition using LSTM networks
* Mobile deployment using TensorFlow Lite
* Support for additional sign languages (ISL/BSL)
* Sentence-level prediction using language models
* Cloud deployment and MLOps integration

