# Deep-Learning-state-classification

# Introduction
This project focuses on fine-grained object state recognition, which is crucial for robotic cooking. Unlike object recognition, which identifies the type of object, state recognition classifies the state of the object (e.g., whole, sliced, chopped). The goal is to enable robots to perform manipulation tasks accurately by recognizing the state of cooking objects.

# Project Overview

# Goal
Design a deep convolutional neural network to classify the state of a cooking object based on an image. For instance, given an image of a "sliced tomato" or "sliced bread", the network should output "sliced".

# Dataset
The dataset includes 9309 images of 17 cooking objects in 11 different states. It can be downloaded [here](https://drive.google.com/file/d/1HU0Z3X3OltW8oUlW_Kkqsz_6kA_ma2tX/view).

Project Components
1. Data Annotation:
   - Annotate frames of cooking objects with bounding boxes and state labels using CVAT.
   - Submit annotations in PASCAL VOC format.
   
2. Neural Network Design and Training :
   - Build a deep convolutional neural network based on the provided sample code.
   - Split the dataset into training and validation sets.
   - Train and validate the model using Python (TensorFlow).
   - Provide a test script for evaluating the trained model.

3. Improvement and Comparison
   - Improve the model using techniques such as data augmentation, batch normalization, and Inception modules.
   - Submit source code, trained models, and performance analysis.

 Requirements
- Language: Python
- Libraries: TensorFlow
- Platform: No other programming languages or platforms are acceptable.

