# Early Detection of Alzheimer's Disease Using Deep Learning

## Project Overview
This project develops a deep learning model to detect Alzheimer’s disease from MRI brain scans using the ResNet18 architecture. The model is trained to classify images into different dementia stages and uses Grad-CAM to visualize the brain regions influencing the prediction.

## Problem Statement
Alzheimer’s disease is a progressive neurological disorder affecting memory and cognitive abilities. Early diagnosis can significantly improve treatment outcomes. This project aims to assist early detection using deep learning techniques applied to MRI images.

## Dataset
MRI brain scan dataset containing the following classes:
-Non-demented
-Very mild-demented
-Mild-demented
-Moderate-demented
Images were resized and normalized before training.

## Technologies Used
Python, Pytorch, resNet18, Numpy, OpenCV, Matplotlib, Grad-CAM

## Computational Workflow
-Data Preprocessing and image Normalisation.
-Train-test data split.
-transfer Learning using ResNet18.
-Model training and Validation.
-Performance Evaluation.
-Grad-CAM visualisation for Interpretability.

## Results
The trained model achieved high classification accuracy in identifying Alzheimer’s stages from MRI scans.
Grad-CAM visualizations highlight the brain regions contributing to the model's prediction, improving interpretability for medical applications.

## Future Improvements
-Deploy the model as a web application.
-Train using larger MRI datasets.
-Experiment with vision transformers
