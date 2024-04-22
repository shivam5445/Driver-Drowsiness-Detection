# Project Summary

We used the Pytorch framework to apply CNN in the dataset. 

The Driver Drowsiness Detection project focuses on implementing a system to detect drowsiness in drivers using computer vision and deep learning techniques. The project involves two main steps:

## 1. Training a CNN Model - 
Initially, a convolutional neural network (CNN) is trained to classify the eyes of drivers as either open or closed. This step is crucial as it forms the basis of detecting drowsiness based on the state of the driver's eyes.

## 2. Real-time Drowsiness Detection - 
Once the CNN model is trained, it is applied in real-time using computer vision techniques, particularly dlib landmarks detection, to accurately locate and analyze the driver's eyes. By monitoring the driver's eyes for a specific duration (typically ten seconds), the system calculates the mean drowsiness level during that period. Based on this analysis, the system can determine whether the driver is sleepy or awake.
