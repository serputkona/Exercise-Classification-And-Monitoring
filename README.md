# Physical Exercise Classification and Monitoring System

## Overview

This project focuses on developing a deep learning model based on ResNet50 for classifying physical exercises from video data, coupled with an algorithm for counting repetitions and estimating calories burned. The primary goal is to automate exercise monitoring, enabling users to effectively track and analyze their workouts for improved fitness and health.

## Methods

- **Deep Learning**: Utilizes the ResNet50 architecture for exercise classification. The model leverages pre-trained weights on ImageNet for effective exercise detection and classification.
- **Computer Vision**: Employs YOLOv8 for detecting and tracking key body points in videos, allowing for detailed analysis of body positions and movements during exercises.

## Tools and Technologies

- **Python**: Primary programming language for developing and testing algorithms.
- **PyTorch**: Framework for deep learning, enabling the use of neural networks and tensor computations.
- **OpenCV**: Computer vision library for video and image processing, used for loading, displaying, and processing video data.
- **NumPy & Math**: Libraries for handling arrays, matrices, and trigonometric calculations essential for accurate movement analysis.

## Results

The algorithm effectively detects key body points and analyzes angles between body parts to identify exercise types and count repetitions. The classification model achieves an accuracy of 99.7%, demonstrating high reliability and effectiveness in automating fitness activity monitoring. Additionally, a method for estimating calories burned was developed, highlighting the practical usefulness of the system for users aiming to optimize their workouts.

