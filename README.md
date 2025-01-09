# MNIST Handwritten Digit Classification using Deep Learning (Neural Network)

## Overview
This project implements a deep learning model to classify handwritten digits from the MNIST dataset. The dataset contains grayscale images of handwritten digits (0-9) with 60,000 training and 10,000 test samples, each of size 28x28 pixels.

The model achieves an accuracy of **96.82%** on the test dataset.

## Dependencies
Ensure you have the following Python libraries installed:

```bash
pip install numpy matplotlib seaborn tensorflow opencv-python
```

## Dataset Description
- **Training Data**: 60,000 images
- **Test Data**: 10,000 images
- **Image Dimensions**: 28x28 pixels
- **Grayscale**: Single channel

## Model Architecture
The neural network consists of the following layers:
1. **Flatten Layer**: Converts the 2D input image into a 1D array.
2. **Dense Layer 1**: Fully connected layer with 50 neurons and ReLU activation.
3. **Dense Layer 2**: Fully connected layer with 50 neurons and ReLU activation.
4. **Dense Layer 3**: Fully connected output layer with 10 neurons and sigmoid activation.

## Results
- **Test Data Accuracy**: 96.82%

## Predictive System Workflow
1. Provide the path to an image of a handwritten digit.
2. The system preprocesses the image by converting it to grayscale, resizing it to 28x28 pixels, and normalizing the pixel values.
3. The image is reshaped to match the input dimensions of the model.
4. The model predicts the digit, and the result is displayed.




