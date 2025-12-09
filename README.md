# Waste Classification Using Transfer Learning

## Overview
This project classifies waste images into **recyclable** and **organic** categories using **transfer learning** with a pre-trained VGG16 model. Both feature extraction and fine-tuning approaches are applied to improve model performance.

## Features
- Uses **VGG16** pretrained model for image feature extraction.
- Fine-tunes top layers of VGG16 for better accuracy.
- Data augmentation applied for improved generalization.
- Compares **feature extraction** vs **fine-tuning** models.
- Visualizes training results and sample predictions.

## Dataset
- Images of recyclable and organic waste.
- Loaded and preprocessed using Keras `ImageDataGenerator`.

## Usage
1. Clone the repository.
2. Install required libraries.
3. Run the notebook to:
   - Load and preprocess the dataset.
   - Train feature extraction and fine-tuned models.
   - Evaluate and visualize predictions.

## Requirements
- Python 3.x
- TensorFlow / Keras
- Matplotlib
- NumPy
