# Potato Leaf Disease Classification using CNN

## Overview
This project focuses on classifying potato leaf diseases using a Convolutional Neural Network (CNN). The model is trained on an image dataset containing healthy and diseased potato leaves, aiming to provide accurate and automated disease detection.

## Objectives
- Develop an image classification model using CNN.
- Train the model on a labeled dataset of potato leaves.
- Evaluate the model’s accuracy in classifying healthy and diseased leaves.

## Dataset
The dataset consists of images categorized into different classes:
- **Healthy Leaves**
- **Diseased Leaves** (various types of infections)

The dataset is preprocessed by resizing images and normalizing pixel values before feeding them into the CNN model.

## Model Architecture
The CNN model consists of multiple layers:
- **Convolutional Layers**: Extract features from images.
- **Pooling Layers**: Reduce spatial dimensions while retaining essential features.
- **Fully Connected Layers**: Classify images based on extracted features.

## Training Process
- The dataset is split into training, validation, and test sets.
- The model is trained using an optimizer and a loss function suited for multi-class classification.
- Training is performed over multiple epochs to improve accuracy.

## Evaluation
- The model's performance is assessed using validation and test datasets.
- Accuracy, loss, and confusion matrices are used as evaluation metrics.

## Results
- The final trained model achieves a high accuracy in distinguishing healthy and diseased potato leaves.
- The results demonstrate the effectiveness of CNNs in plant disease classification.

## Usage
1. Load the trained model.
2. Provide an image of a potato leaf.
3. The model predicts whether the leaf is healthy or diseased.

## Future Improvements
- Enhance model performance by using advanced architectures like ResNet.
- Expand the dataset to include more disease categories.
- Deploy the model as a web or mobile application for real-world use.

## Contributors
- [Upendra Raj Joshi](https://github.com/Upendra48)
- [Kalpana Acharya](https://github.com/kaps04)

## License
This project is open-source and available under the MIT License.
