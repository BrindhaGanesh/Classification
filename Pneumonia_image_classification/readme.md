PneumoniaMNIST Image Classification

This project implements a binary image classification model to detect pneumonia from chest X-ray images using the PneumoniaMNIST dataset from the MedMNIST collection. The goal is to classify images as either "normal" (0) or "pneumonia" (1) using a convolutional neural network (CNN) with PyTorch.

Dataset

The PneumoniaMNIST dataset is automatically downloaded when running the notebook. Key details:


Classes: 0 (normal), 1 (pneumonia).

Channels: 1 (grayscale).

Image Size: 28x28 pixels.


Splits:

Training: 4,708 images
Validation: 524 images
Test: 624 images

Future Improvements





Implement and test data augmentation techniques.



Define and train a CNN model with Cross-Entropy or BCE Loss.



Evaluate performance using metrics like accuracy, precision, recall, and AUC.



Tune hyperparameters (e.g., learning rate, batch size).

Acknowledgments





MedMNIST for providing the PneumoniaMNIST dataset.



PyTorch for the deep learning framework.