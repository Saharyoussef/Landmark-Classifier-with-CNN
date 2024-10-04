# Landmark Classifier Project

## Project Overview

This project aims to develop a landmark classifier that automatically predicts the location of images based on discernible landmarks. Photo-sharing services often lack location metadata for uploaded images, which can hinder features like automatic tagging and organization. This project addresses that challenge by employing deep learning techniques to identify landmarks in images.

### Key Objectives:

1. **Data Preprocessing**: Prepare and visualize the dataset for model training.
2. **Model Development**: Build and train Convolutional Neural Networks (CNNs) from scratch and through transfer learning.
3. **Model Evaluation**: Compare the performance of various CNN architectures to identify the best-performing model.
4. **Deployment**: Create a user-friendly application that allows users to upload images and receive predictions of the landmarks depicted.

By automating landmark detection and classification, this project enhances the functionality of photo-sharing platforms, improving user experience and enabling advanced features based on image content.


## Project Steps

The project consists of three main phases, each detailed in corresponding Jupyter Notebooks:

1. **Create a CNN to Classify Landmarks (from Scratch)**: 
   - Visualize and preprocess the dataset for training.
   - Build a convolutional neural network from scratch.
   - Describe decisions regarding data processing and network architecture.
   - Export the best network using Torch Script.

2. **Create a CNN to Classify Landmarks (using Transfer Learning)**:
   - Investigate various pre-trained models and select one for classification.
   - Train and test the transfer-learned network.
   - Explain the rationale behind the chosen pre-trained network.
   - Export the best transfer learning solution using Torch Script.

3. **Deploy Your Algorithm in an App**:
   - Use the best model to create a simple application for users to identify landmarks in images.
   - Test the model and reflect on its strengths and weaknesses.

## Notebooks

- **cnn_from_scratch.ipynb**: Create a CNN from scratch.
- **transfer_learning.ipynb**: Use transfer learning for classification.
- **app.ipynb**: Deploy the best model in an application and generate a submission file.

## Environment and Dependencies

You can view this project in two ways: using the AWS Sagemaker Studio or your local machine.

