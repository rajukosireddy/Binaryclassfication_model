# Binaryclassfication_model
This repository showcases the implementation of a binary image classification model using TensorFlow and Keras. The model is trained to classify images into two categories: cats and dogs. 

## Features
- **Data Augmentation:** Enhances model generalization through ImageDataGenerator for training data augmentation.
- **CNN Architecture:** Utilizes a Convolutional Neural Network (CNN) with convolutional, max-pooling, and dense layers.
- **Training History Visualization:** Plots training and validation accuracy/loss for model assessment.
- **Image Plotting Functions:** Visualizes augmented and training images.

## Model Architecture
- Input Layer: Convolutional layer with ReLU activation.
- Hidden Layers: MaxPooling and Convolutional layers.
- Flatten Layer.
- Dense Layers: Fully connected layers with ReLU activation.
- Output Layer: Dense layer with 2 neurons for binary classification (cats and dogs).
