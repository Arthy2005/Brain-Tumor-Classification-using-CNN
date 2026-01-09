# Brain-Tumor-Classification-using-CNN
Brain Tumor Classification using CNN
Overview

This project implements a Convolutional Neural Network (CNN) to classify brain MRI images into tumor and non-tumor categories. The model is built using TensorFlow/Keras and follows a complete deep learning pipeline including data preprocessing, training, evaluation, and inference.

Dataset

The dataset is organized into two folders:

brain_tumor_dataset - yes (tumor images) and no (non-tumor images)


All images are resized to 128×128 pixels and processed as RGB images. The data is split into 70% training and 30% testing.

Preprocessing

Image resizing and RGB validation

Pixel normalization to the range [0, 1]

One-hot encoding of labels

Train-test split for evaluation

Model

The CNN architecture includes:

Convolutional layers with ReLU activation

Batch normalization and max pooling

Dropout for regularization

Fully connected layers with softmax output

The model is trained using categorical cross-entropy loss and the Adamax optimizer, with accuracy used as the evaluation metric.

Results

The trained model is able to classify MRI images into tumor and non-tumor classes and provides confidence scores for predictions.

Technologies Used

Python, TensorFlow/Keras, NumPy, Scikit-learn, Matplotlib, PIL
