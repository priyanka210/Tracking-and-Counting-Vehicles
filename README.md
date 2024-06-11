# Tracking and Counting Vehicles

## Overview
This research explores vehicle detection techniques for traffic surveillance systems. By integrating CCTV cameras, the system detects, tracks, and counts vehicles with high accuracy using image processing methods such as Haar Cascades and the Viola Jones Algorithm.

## Abstract
This research work explores vehicle detection techniques for traffic surveillance systems. By integrating CCTV cameras for detecting cars, we use Haar Cascades and Viola Jones Algorithm to identify, track, and count vehicles with an accuracy of up to 78%.

## Introduction
Vehicle detection and counting are crucial for traffic management in cities. The primary objective is to detect and count cars accurately on roads, highways, and small lanes. The system uses Haar Cascades for car detection, tracking each car in a selected region of interest until it leaves the area.

## Literature Survey
Object recognition is a method developed over time using various algorithms for identifying objects in images. Despite the challenges, it remains a crucial component of traffic management systems to address issues like traffic congestion and accidents.

## Methodology
The methodology consists of several steps as outlined below:

### Input Frames
The system processes an existing video sequence, dividing it into frames, which are then transformed into gray-level frames for input.

### Object Detection
Haar Cascade Classifier, also known as the Viola Jones method, is used for object detection. This method involves Haar-like features, integral images, and AdaBoost learning to detect cars.

### Selection of Region of Interest
A specific region of an image is selected as the region of interest (ROI) to focus on vehicle detection and tracking.

### Object Tracking
The system tracks the position (x, y) of each detected vehicle, comparing it with previous frames to identify and count new or existing vehicles.

### Object Counting
Vehicles passing through the ROI are tracked and counted based on their position. New positions are added as new objects, while existing positions are updated for recognized vehicles.

## Results and Experiments
Results are shown through various figures and screenshots demonstrating the input frames, transformed gray frames, regions of interest, and vehicle detection and counting accuracy.

## Conclusion
This research designs a system for vehicle classification and counting using Haar Cascade Classifiers. The system operates automatically without human interference, providing accurate vehicle detection and counting on roads.
