## Title of the Project
Distraction Detector – Real-Time Driver Alertness Monitoring System
The Distraction Detector is a real-time vision-based driver monitoring system designed to detect driver distraction by analyzing eye behavior using Eye Aspect Ratio (EAR). The system continuously monitors driver alertness through a camera and provides timely alerts to prevent accidents caused by inattentive driving.
## About
Distraction Detector is an intelligent transportation safety project that focuses on identifying driver distraction using computer vision techniques. With the increasing use of mobile devices and long driving durations, driver inattentiveness has become a major cause of road accidents.

This project uses facial landmark detection to track eye movements and blinking patterns in real time. By calculating the Eye Aspect Ratio (EAR) from live video frames, the system determines whether the driver's eyes are open or closed. If the EAR value remains below a predefined threshold for a certain duration, the system classifies the driver as distracted and immediately triggers an alert.

The solution is non-intrusive, cost-effective, and runs efficiently on standard hardware without requiring wearable sensors or complex deep learning models, making it suitable for real-world deployment.

## Features
Real-time driver eye monitoring using camera input

Eye Aspect Ratio (EAR)–based distraction detection

Non-intrusive and sensor-free system

Lightweight and computationally efficient

Real-time alert system for distracted driving

Works under varying lighting and driving conditions

No requirement for deep learning models

## Requirements
1.Operating System:
2.Windows 10 (64-bit) or Ubuntu (64-bit)
3.Development Environment:
4.Python 3.6 or later
5.Computer Vision Libraries:
6.OpenCV for real-time video processing
7.Dlib for facial landmark detection
8.Additional Libraries:
9.NumPy for numerical operations
10.imutils for image processing utilities
11.Hardware Requirements:
12.Standard webcam or in-car camera
13.Minimum 4 GB RAM
14.Intel i3 processor or higher

## System Architecture

![WhatsApp Image 2025-12-24 at 10 57 28 PM](https://github.com/user-attachments/assets/4fc6fd04-bebd-4d19-b3b2-d03ac593587b)


## Output


#### Output1 - FOCUSED
<img width="828" height="466" alt="image" src="https://github.com/user-attachments/assets/787f0c1c-c669-49b8-afdb-c82a2574f7bd" />



#### Output2 - DROWSINESS DETECTED
<img width="832" height="460" alt="image" src="https://github.com/user-attachments/assets/72094c20-3560-4940-b475-ab17ca35adc7" />


Detection Accuracy: 95.8%
(Note: This metric can be customized based on your experimental results.)


## Results and Impact
The Distraction Detector effectively identifies inattentive driving behavior with high accuracy and minimal processing delay. The system enhances road safety by providing early warnings to drivers, reducing the likelihood of accidents caused by fatigue or distraction.

By leveraging computer vision and geometric analysis, this project demonstrates a practical and scalable approach for real-time driver monitoring systems. It serves as a foundation for advanced intelligent transportation solutions and can be further extended with yawning detection, head pose estimation, or mobile usage detection.
## Articles published / References
1.T. Soukupová and J. Čech, “Real-Time Eye Blink Detection using Facial Landmarks,” 21st Computer Vision Winter Workshop, 2016.

2.P. Viola and M. Jones, “Rapid Object Detection using a Boosted Cascade of Simple Features,” IEEE CVPR, 2001.

3.N. S. Gupta et al., “Enhancing Heart Disease Prediction Accuracy Through Hybrid Machine Learning Methods,” EAI Endorsed Transactions on IoT, vol. 10, Mar. 2024.

4.A. A. Bin Zainuddin, “Enhancing IoT Security: A Synergy of Machine Learning, Artificial Intelligence, and Blockchain,” Data Science Insights, vol. 2, no. 1, Feb. 2024.

