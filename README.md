# Brain Tumor Detection Project

This repository contains code for a brain tumor detection project implemented in Python using TensorFlow and Keras. The project focuses on using convolutional neural networks (CNNs) to classify brain MRI images into tumor and non-tumor categories.

## Overview

The project involves the following steps:

1. Data Preprocessing: The MRI images are preprocessed, including cropping to focus on the brain region and resizing for uniformity.

2. Data Augmentation: Augmentation techniques are applied to increase the dataset size and improve model generalization.

3. Model Development:
   - Initial Model: A VGG19 model with frozen convolutional base layers is trained on the dataset.
   - Fine-tuning: The top layers of the pretrained VGG19 model are unfrozen and fine-tuned on the dataset.
   - Unfrozen Model: The entire VGG19 model is unfrozen and trained on the dataset.

4. Model Evaluation: The trained models are evaluated on validation and test datasets to assess their performance.

## Files and Directories

- `data`: Contains the dataset of brain MRI images.
- `model_weights`: Stores the trained model weights.
- `README.md`: Provides an overview of the project and instructions for running the code.

## Requirements

The following libraries are required to run the code:

- TensorFlow
- Keras
- OpenCV
- Matplotlib
- Seaborn
- Numpy
- Pandas
