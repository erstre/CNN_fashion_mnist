# Convolutional Neural Network (CNN)
Python implementation of Convolutional Neural Network (CNN) for image classification.


## Description
[Convolutional Neural Network (CNNs)](https://en.wikipedia.org/wiki/Convolutional_neural_network) are designed to automatically and adaptively learn spatial hierarchies of features from input images by using convolutional layers, pooling layers, and fully connected layers.

Convolutional layers apply a set of filters to an input image to create a feature map that captures local patterns and structures. Pooling layers then reduce the size of the feature map by summarizing groups of adjacent features. Finally, fully connected layers take the output of the convolutional and pooling layers and use it to classify the input image.

CNNs have proven to be very effective in many image recognition and computer vision tasks, such as object detection, facial recognition, and image segmentation. They have also been applied to other types of data, such as speech and natural language processing.

In this project, we employ a CNN architecture for the problem of image classification on the [Fashion-MNIST dataset](https://keras.io/api/datasets/fashion_mnist/). Specifically this code:

- Constructs a CNN architecture using TensorFlow and Keras.
- It trains the model on Fashion-MNIST dataset.
- Classifies the images on the test dataset.
- Displays some the predictions that were made.

### Prerequisites

The following software needs to be installed.

- Python
- TensorFlow

For executing the code run the following command:
```bash
python3 fashion_cnn.py
```

## Authors

[Errikos Streviniotis](https://www.linkedin.com/in/errikos-streviniotis/)
