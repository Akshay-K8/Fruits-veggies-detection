# Fruit Detection Using CNN

This project is a Convolutional Neural Network (CNN) based model designed to detect and classify different types of fruits from images. The model has been trained on a dataset of fruit images and is capable of providing real-time predictions using a webcam. The application is designed for various scenarios, such as identifying fruits in markets, automated sorting systems, or nutritional analysis tools.

## Features

- **Real-Time Detection**: Uses a webcam to detect and classify fruits in real-time.
- **High Accuracy**: Achieves high accuracy with minimal overfitting through techniques like data augmentation, regularization, and learning rate adjustments.
- **User Interaction**: Allows users to capture images and displays the detected fruit name dynamically.

## Requirements

- Python 3.x
- TensorFlow 2.x
- OpenCV
- Numpy

Use the package manager [pip](https://pip.pypa.io/en/stable/) to install the required packages:

```bash
pip install tensorflow opencv-python numpy
```

## Model Training
The model was trained on a dataset of fruit images using a Convolutional Neural Network (CNN). Training was performed over multiple epochs with the following strategies to enhance accuracy and generalization:

**Data Augmentation:** Rotations, shifts, and flips were applied to the training images to make the model more robust.
**Regularization:** L2 regularization and dropout were used to prevent overfitting.
**Learning Rate Scheduler:** The learning rate was dynamically adjusted during training to ensure smooth convergence.

## Training Results
Below are the results of the last 10 epochs:
```bash
Epoch 10/30: loss: 0.5628 - accuracy: 0.8148 - val_loss: 0.3881 - val_accuracy: 0.8974
Epoch 11/30: loss: 0.4762 - accuracy: 0.8440 - val_loss: 0.3556 - val_accuracy: 0.8974
Epoch 12/30: loss: 0.4402 - accuracy: 0.8629 - val_loss: 0.3416 - val_accuracy: 0.9145
...
Epoch 19/30: loss: 0.1981 - accuracy: 0.9400 - val_loss: 0.2554 - val_accuracy: 0.9516
```
