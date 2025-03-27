# Image Classification with Transfer Learning

This repository contains code for an image classification project using transfer learning with pre-trained models from Keras. The project demonstrates how to use pre-trained models like VGG16 and ResNet50 as a base and retrain them for custom image classification tasks.

## Project Overview

This project uses the Keras deep learning framework to:
1. Load and preprocess image datasets
2. Initialize pre-trained models (VGG16, ResNet50)
3. Adapt these models for custom classification tasks
4. Train the modified models
5. Evaluate model performance

The code is structured to work with image datasets organized in directories, where each subdirectory represents a class.

## Dataset

The project uses a dataset with 7 classes:
- '5'
- '10'
- '20'
- '50'
- '100'
- '200'
- '500'

Each class contains multiple images (70 images in total across all classes). The dataset is split into training and validation sets.

## Requirements

To run this project, you need the following libraries:
- Keras
- TensorFlow
- NumPy
- Pandas
- Matplotlib
- PIL (Python Imaging Library)
