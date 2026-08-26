# Plant Disease Detection

Deep learning project for classifying plant leaf diseases using
TensorFlow, Keras, and EfficientNetB0.

## Project Overview

This project uses transfer learning with EfficientNetB0 to classify
plant leaf images into different disease categories.

## Tech Stack

- Python
- TensorFlow
- Keras
- EfficientNetB0
- Scikit-learn
- NumPy
- Pandas
- Matplotlib

## Dataset

PlantVillage dataset.

The dataset is not included in this repository because of its size.

## Model Architecture

```text
Input Image
    ↓
224 × 224 × 3
    ↓
Data Augmentation
    ↓
EfficientNetB0
    ↓
Global Average Pooling
    ↓
Dropout
    ↓
Dense Layer
    ↓
Softmax
    ↓
Disease Prediction
