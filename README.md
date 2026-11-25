# Skin Disease Classification Using CNN and Transfer Learning

## Project Overview

This project focuses on skin disease classification using Deep Learning techniques.

Two models are implemented and compared:

1. Custom Convolutional Neural Network (CNN)
2. Transfer Learning using ResNet50

The HAM10000 dataset is used for training and evaluating the models.

## Dataset

**Dataset Name:** HAM10000 (Human Against Machine with 10000 training images)

**Dataset Source:** Harvard Dataverse

**Download Dataset:** https://doi.org/10.7910/DVN/DBW86T

The dataset contains approximately 10,015 dermatoscopic images belonging to seven different skin lesion categories.

### Dataset Files

- HAM10000_metadata.csv
- HAM10000_images_part_1.zip
- HAM10000_images_part_2.zip

**Note:** Due to the large size of the image dataset, the image ZIP files are not uploaded to this GitHub repository. Download them from the original dataset source.

## Models Implemented

### 1. Custom CNN
- Convolutional layers
- ReLU activation
- Max Pooling
- Dropout
- Fully Connected Layers

### 2. Transfer Learning – ResNet50
- Pretrained ImageNet weights
- Feature extraction
- Fine-tuning
- Seven-class classification

## Technologies Used

- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Pillow
- Torchvision
- Jupyter Notebook



Download the HAM10000 image dataset and metadata from the source linked above.

Extract both image ZIP files and update the notebook paths if required.

## Model Evaluation

Both models are evaluated using:

- Accuracy
- Precision
- Recall
- Macro F1 Score
- Confusion Matrix
- Classification Report

