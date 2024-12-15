# Machine_Learning_task
# MNIST Image Classification with Neural Networks

This project demonstrates the use of neural networks for image classification using the MNIST dataset, which contains handwritten digits (0-9). The model is built using TensorFlow and Keras, with the goal of classifying grayscale images into the corresponding digits.

## Steps Followed:
1. **Data Collection**: The MNIST dataset was loaded, containing 60,000 training images and 10,000 test images.
2. **Data Preprocessing**: Images were normalized to a [0, 1] range, and labels were converted to one-hot encoding for classification.
3. **Model Definition**: A neural network was defined with one flatten layer, two hidden layers, and an output layer with 10 neurons (for 10 classes).
4. **Model Compilation**: The model was compiled using the Adam optimizer, categorical crossentropy loss, and accuracy as the evaluation metric.
5. **Model Training**: The model was trained for 10 epochs, with a batch size of 32, using a validation split of 20%.
6. **Model Evaluation**: The model's performance was evaluated on the test data, achieving a high accuracy.
7. **Save the Model**: The trained model was saved to a file for later use.
8. **Make Predictions**: The model was loaded, and predictions were made on the test dataset.

## Requirements:
- Python 3.x
- TensorFlow
- Matplotlib

## Instructions:
1. Clone this repository.
2. Install the necessary libraries:
3. Pip install Tensorflow Matplotlib.
4. Run `mnist_classifier.py` to train and evaluate the model.



   
