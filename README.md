Hand Gesture Recognition Using CNN

This project implements a Convolutional Neural Network (CNN) to classify hand gestures from image data. The goal is to create an intuitive human-computer interaction system through gesture-based control. The model was trained using a dataset of hand gesture images acquired through the Leap Motion sensor.

Key Features:

Dataset preprocessed using ImageDataGenerator for rescaling and train-validation split.

CNN architecture with multiple convolutional layers, max-pooling, and dropout for improved accuracy.

Model performance evaluated using accuracy and loss metrics for both training and validation sets.

Visualization of sample images and training history (accuracy/loss).

Model saved for future predictions and deployed on unseen gesture images.

How to Use:

Upload the dataset and extract it.

Train the model with the provided code.

Use the saved model to make predictions on new hand gesture images.

Dependencies:

TensorFlow

Keras

NumPy

Matplotlib
