# ML-Based Washer Counting System

A YOLOv8-based computer vision system for detecting washers, classifying them as good or bad, and counting them after they cross a defined line.

## Overview

The project was developed as a machine-learning inspection system using images collected from the washer setup. The workflow covers image capture, dataset preparation, model training, detection, and counting.

## Dataset

- **1000+** self-collected images
- **657** training images
- **20** validation images
- Classes include **good** and **bad** washers

## Method

The system uses YOLOv8 for object detection.

**Workflow:**  
Camera → Image Capture → YOLOv8 Detection → Good/Bad Classification → Line Crossing → Washer Count

## Software

- Python
- YOLOv8
- Roboflow
- OpenCV

The project was developed and tested on systems without a dedicated GPU, including an Intel i5-1235U and AMD Ryzen 5 3600.

## Project Files

The project includes scripts for image capture, model training, testing, detection, and washer counting.

## Author

**Tanisha Gupta**  
B.Tech Electronics Engineering, VIT Vellore  
Specialization: VLSI Design and Technology
