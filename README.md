# Image Recognition Model Training and Deployment Using Teachable Machine and Python

## Project Overview

The purpose of this task was to develop an image recognition model capable of classifying images into predefined categories. The project was implemented using Teachable Machine by Google, a user-friendly web-based tool for training machine learning models, followed by writing a Python script to load the trained model, accept input images, and output predictions.

⸻

## Objectives
 - Train an image classification model with a custom dataset.
 - Evaluate the model’s performance on test samples.
 - Export the trained model for integration into Python workflows.
 - Develop a Python script to:
 - Load the trained model.
 - Preprocess input images.
 - Predict the image class.
 - Display or return the prediction result.

⸻

## Tools and Technologies
 - Teachable Machine by Google: For training and exporting the model.
 - TensorFlow / Keras: For model loading and inference.
 - Python (with supporting libraries):
 - tensorflow
 - numpy
 - PIL (Python Imaging Library) for image processing

⸻

## Implementation Steps

Step 1: Model Training
 1. Dataset Preparation:
 - Collected sample images for each class.
 -  Uploaded images to Teachable Machine, labeling them into their respective categories.
 2. Model Training:
 - Configured the image project in Teachable Machine.
 - Initiated the training process, which used transfer learning under the hood.
 - Observed training metrics such as accuracy and loss.
 3. Model Evaluation:
 - Tested the model with additional images to verify predictions.
 - Adjusted dataset size if needed to improve performance.
 4. Model Export:
 - Exported the trained model in TensorFlow (SavedModel) format.
 - Downloaded the model files for local use.

⸻

Step 2: Python Integration

Developed a Python script to load the exported model and make predictions on new images by google colab.
## Results and Evaluation
 - The trained model successfully classified test images with satisfactory accuracy.
 - The Python script correctly loaded the model and provided predictions.
 - The solution demonstrated the feasibility of integrating a Teachable Machine model into a Python environment.
