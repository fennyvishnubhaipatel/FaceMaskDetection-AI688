# FaceMaskDetection-AI688
 
## Project Overview
This project focuses on developing an Artificial Intelligence system to automatically detect whether a person is wearing a face mask or not. The system uses deep learning and computer vision techniques to classify images and detect faces in real-time.

The proposed approach combines Convolutional Neural Networks (CNN) for image classification and YOLOv8 for real-time object detection. The goal of the project is to build an efficient model that can detect mask usage in images or video streams.

This project is developed as part of the AI688 Artificial Intelligence course.

## Team Members:-
Fenny Patel  
Rohit Saresa

## Project Objectives
The main objectives of this project are:

- Develop a deep learning model for face mask detection
- Classify images into two categories: mask and no mask
- Implement real-time face detection using YOLOv8
- Evaluate model performance using standard evaluation metrics

## Technologies Used
- Python
- Deep Learning
- Computer Vision
- Convolutional Neural Networks (CNN)
- YOLOv8 (In future)
- OpenCV
- TensorFlow / PyTorch

## Dataset

Dataset used for this project:

Face Mask Detection Dataset

Source: Kaggle

Dataset Link  
https://www.kaggle.com/datasets/andrewmvd/face-mask-detection

The dataset contains images of people wearing masks and people without masks. It also includes annotation files for object detection tasks.

## Methodology

The proposed system follows the pipeline below:

Dataset Collection  
↓  
Image Preprocessing  
↓  
YOLOv8 Face Detection  
↓  
CNN Mask Classification  
↓  
Final Prediction (Mask / No Mask)

First, YOLOv8 detects the location of faces in the image. Then the CNN model classifies the detected face as either wearing a mask or not wearing a mask.

## Project Structure

FaceMaskDetection-AI688

dataset:-
Contains dataset images and annotations

code  :-
Contains Python implementation of mask detection model

report :-
Contains project report and documentation

presentation  :-
Contains project presentation slides

## Evaluation Metrics

The performance of the model will be evaluated using:

Accuracy  
Precision  
Recall  
F1 Score

These metrics help measure how well the model detects mask usage.

## Current Progress (Midterm)

Completed Tasks

- Literature review
- Dataset collection
- Data preprocessing
- Project architecture design

Ongoing Tasks

- Model training
- Performance evaluation
- System testing

## Expected Results

The expected outcome of this project is a reliable AI model capable of accurately detecting face masks in images and real-time video streams. The system can potentially be used in public safety environments such as airports, hospitals, and public transportation systems.

## Future Work

Future improvements may include:

- Real-time camera integration
- Improving model accuracy
- Detecting incorrectly worn masks
- Expanding dataset for better robustness

## References

1. Real-Time Facemask Detection for Preventing COVID-19 Spread Using Transfer Learning Based Deep Neural Network  
https://www.mdpi.com/2079-9292/11/14/2250/pdf

2. A Deep Learning-Based Approach for Real-Time Facemask Detection  
https://arxiv.org/pdf/2110.08732.pdf

3. Face Mask Detection Using Convolutional Neural Networks  
https://arxiv.org/pdf/2008.04745.pdf

## Course Information

Course: AI688 Artificial Intelligence  
Institution: Long Island University 
Semester: Spring 2026
