# Handwritten Digit Recognition using CNN (MNIST Dataset)

This project demonstrates the implementation of a Convolutional Neural Network (CNN) for recognizing handwritten digits using the MNIST dataset. The dataset consists of 60,000 training images and 10,000 test images, where each image is a 28x28 grayscale image representing digits from 0 to 9.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Model Architecture](#model-architecture)
- [Installation](#installation)
- [Usage](#usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [Contributing](#contributing)
- [License](#license)

## Introduction
The goal of this project is to build a deep learning model that can accurately classify handwritten digits. The model is trained using the MNIST dataset, a widely used benchmark in the field of machine learning.

## Dataset
The MNIST dataset is a collection of 70,000 images of handwritten digits. It is split into a training set of 60,000 images and a test set of 10,000 images. Each image is a 28x28 pixel grid with pixel values ranging from 0 (black) to 255 (white).

## Model Architecture
The Convolutional Neural Network (CNN) used in this project consists of the following layers:

1. **Input Layer**: 28x28 grayscale images.
2. **Convolutional Layer**: 32 filters, 3x3 kernel, ReLU activation.
3. **MaxPooling Layer**: 2x2 pooling size.
4. **Convolutional Layer**: 64 filters, 3x3 kernel, ReLU activation.
5. **MaxPooling Layer**: 2x2 pooling size.
6. **Convolutional Layer**: 64 filters, 3x3 kernel, ReLU activation.
7. **Flatten Layer**: Converts 2D matrix to 1D vector.
8. **Dense Layer**: 64 neurons, ReLU activation.
9. **Output Layer**: 10 neurons (one for each digit), Softmax activation.

## Installation
To run this project, you need to have Python installed along with the necessary libraries. Follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/Ravikanth5195/Handwritten-digit-recognition.git
    cd Handwritten-digit-recognition
    ```

2. Install the required packages:
    ```bash
    pip install tensorflow matplotlib
    ```

## Usage
Once the dependencies are installed, you can run the project by executing the following command:

```bash
python mnist_cnn.py
