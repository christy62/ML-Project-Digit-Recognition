# Digit Recognition

A handwritten digit recognition project using a manual dataset and a neural network built with PyTorch.

## About the Project

The project focuses on recognising handwritten digits from 0 to 9. I created my own dataset of handwritten digits, with each image represented as a 25 × 25 pixel array.

The dataset was used to train and test a simple neural network.

## Technologies Used
- Python
- PyTorch
- NumPy
- Pandas
- Matplotlib

## Model Details
- Input: 25 × 25 pixel images
- Hidden layer: 128 neurons
- Activation function: ReLU
- Output: 10 classes (digits 0–9)
- Loss function: Cross-Entropy Loss
- Optimizer: Adam

## Results

The model was evaluated using a separate test set. A confusion matrix was also generated to examine the classification results for each digit.

### Confusion Matrix

![Confusion Matrix](confusion_matrix.png)
[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](YOUR_COLAB_LINK)

