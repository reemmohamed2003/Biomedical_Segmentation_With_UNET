# Breast Ultrasound Image Segmentation Using U-Net

## Introduction

This project focuses on breast ultrasound image segmentation using a U-Net deep learning model implemented with TensorFlow and Keras.

The main objective is to automatically segment the region of interest (ROI) in breast ultrasound images by predicting a segmentation mask for each input image.

## Dataset

The project uses the Breast Ultrasound Images Dataset from Kaggle.

The dataset contains breast ultrasound images categorized into:

- Benign
- Malignant
- Normal

The dataset also provides corresponding masks that identify the regions of interest in the ultrasound images.

## Project Workflow

### 1. Data Loading and Preparation
- Explore the dataset structure.
- Load the ultrasound images and corresponding masks.
- Organize the data for further analysis and modeling.

### 2. Exploratory Data Analysis (EDA)
- Analyze the distribution of images across different classes.
- Visualize examples from the dataset.
- Calculate and visualize the average masks for each class.

### 3. Data Preprocessing
- Prepare images and masks for the segmentation task.
- Resize images and masks to a consistent input size.
- Normalize the image data.

### 4. U-Net Modeling

A U-Net architecture is built using Keras for semantic segmentation.

The model consists of:
- An encoder for feature extraction.
- A decoder for reconstructing the segmentation map.
- Skip connections for preserving spatial information.

### 5. Model Training

The U-Net model is trained using breast ultrasound images as inputs and their corresponding segmentation masks as ground-truth labels.

### 6. Evaluation

The trained model is evaluated on the segmentation task by comparing the predicted masks with the ground-truth masks.

## Technologies Used

- Python
- TensorFlow
- Keras
- NumPy
- OpenCV
- Matplotlib
- U-Net
- Deep Learning
- Computer Vision

## Dataset Source

Breast Ultrasound Images Dataset — Kaggle
