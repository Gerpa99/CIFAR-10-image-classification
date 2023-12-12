# CIFAR10 Image Classification

![CIFAR10 Image](link_a_la_imagen_o_logo_del_proyecto)

## Overview

CIFAR10 Image Classification is a project that explores the CIFAR-10 dataset, focusing on the classification of images using deep learning models. LeNet and DenseNet architectures are employed for the classification task, with an emphasis on image augmentation techniques and model evaluation.

## Table of Contents

- [Introduction](#cifar10-image-classification)
- [Models](#models)
  - [LeNet](#lenet)
  - [DenseNet](#densenet)
- [Image Augmentation](#image-augmentation)
- [Training Models](#training-models)
- [Evaluation](#evaluation)
- [Getting Started](#getting-started)
- [Dependencies](#dependencies)
- [Contributing](#contributing)
- [License](#license)

## Models

### LeNet

The LeNet model, inspired by Yann LeCun's work, forms the foundational model for CIFAR10 Image Classification. It undergoes experimentation with image augmentation techniques to enhance its performance.

### DenseNet

The project introduces DenseNet, a robust convolutional neural network architecture, to delve into the complexities of the CIFAR-10 dataset. Dense blocks and transition layers enable a detailed exploration of image features.

## Image Augmentation

The initial phase involves expanding the LeNet model and exploring various image augmentation techniques. For details on image augmentation, refer to the [PyTorch documentation](https://pytorch.org/vision/stable/transforms.html).

## Training Models

Standard training and validation procedures are followed to train and evaluate the models. Functions for training epochs, validation, and model evaluation have been crafted for seamless experimentation.

## Evaluation

After training, the models are evaluated on the test data. Robustness is assessed by simulating real-world scenarios, applying horizontal and vertical flips to the images.

## Getting Started

To explore CIFAR10 Image Classification and run the models locally, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/CIFAR10-image-classification.git
