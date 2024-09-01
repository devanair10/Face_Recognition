# Face Recognition Using PCA and ANN

This project is an implementation of a face recognition system using Principal Component Analysis (PCA) and Artificial Neural Networks (ANN). The notebook face_recognition.ipynb contains the complete code and step-by-step explanation of the process, focusing on face recognition using images of People.

## Table of Contents
### Introduction
### Requirements
### Dataset
### Implementation
### PCA for Feature Extraction
### ANN for Classification
### Results
### Usage
### Conclusion
### References
## Introduction
This project explores the combination of PCA for dimensionality reduction and ANN for classification in a face recognition task. The goal is to accurately recognize faces by reducing the high-dimensional face data into a lower-dimensional feature space using PCA and then classifying the images using an ANN.

## Requirements
To run this, you need the following Python packages installed:

### numpy
#### matplotlib
#### sklearn
#### keras
#### tensorflow

## Implementation
Those images are processed and fed into the PCA for feature extraction.
PCA is used to reduce the dimensionality of the input images. This step transforms the high-dimensional image data into a lower-dimensional feature space, capturing the most significant features that contribute to face recognition.

## ANN for Classification
The extracted features from the PCA are then passed through an Artificial Neural Network for classification. The ANN is trained to recognize the faces based on the reduced feature set.

## Results
This provides detailed outputs showing the PCA-reduced images, the training process of the ANN, and the final classification results. The model's accuracy and performance metrics are also discussed.

## Conclusion
This project demonstrates the effectiveness of combining PCA and ANN for face recognition tasks. PCA efficiently reduces the data dimensionality, while the ANN performs robust classification based on the extracted features.
