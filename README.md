# Handwritten digit recognition with TensorFlow

Python code that trains a CNN model on the MNIST dataset of handwritten digits (0-9). It then uses the trained model to predict the digits in user-provided images.

### Code includes:

- **Data Loading**: Loads the MNIST dataset and preprocesses the images.
- **Model Building**: Creates a CNN architecture with convolutional and pooling layers for feature extraction, followed by dense layers for classification.
- **Model Training**: Trains the model on the MNIST data for a specified number of epochs.
- **Model Evaluation**: Evaluates the model's performance on unseen test data.
- **Model Saving**: Saves the trained model for future use.
- **Image Prediction**: Defines functions to load and preprocess new images, make predictions using the saved model, and count the occurrences of each predicted digit.
