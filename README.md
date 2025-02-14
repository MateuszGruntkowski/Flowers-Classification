# Image Classification with CNNs: Flower Classification

This project demonstrates image classification using deep learning, specifically Convolutional Neural Networks (CNNs). The goal of the project is to build a model that can classify images of flowers into five distinct categories: **Daisy, Dandelion, Roses, Sunflowers, and Tulips**.

## Dataset
The project uses a publicly available dataset containing approximately 3,700 flower images categorized into five sub-directories, one per class. The dataset can be easily downloaded from [TensorFlow Datasets](https://www.tensorflow.org/datasets).

## Model
The model is built using the Keras library and consists of:
- **Convolutional layers** to extract features from images.
- **Pooling layers** to reduce spatial dimensions and retain important information.
- **Dense output layer** for multi-class classification.

The model is trained on a training dataset and validated on a validation dataset to evaluate its performance.

## Results
The model achieves high accuracy on the validation dataset and is capable of classifying new flower images with reasonable accuracy.

## Usage
To run this project, you need to install the **TensorFlow** and **Keras** libraries. The project code is available in a Colab notebook for easy execution. 
