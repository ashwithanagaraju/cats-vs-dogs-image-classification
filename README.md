# Cats vs Dogs Image Classification

## Overview
This project performs binary image classification using a Convolutional Neural Network (CNN). It includes image preprocessing, augmentation, model training, validation monitoring, and accuracy-based evaluation on a test set.

## Dataset
The Kaggle Dogs vs Cats dataset is used.  
Each filename contains the label (“cat” or “dog”).  
Images are loaded, resized, normalized, and then passed into the CNN.

## Methodology
- Image resizing and normalization  
- Data augmentation techniques  
- CNN model implemented using TensorFlow/Keras  
- Early stopping to prevent overfitting  
- Evaluation using accuracy and confusion matrix  

## How to Run
Install dependencies:
```
pip install -r requirements.txt
```
Open and execute:
cats-vs-dogs-image-classification.ipynb
