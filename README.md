# Neural Network for Handwritten Digits Classification

This project implements a neural network to classify handwritten digits (0-9) using the MNIST dataset. The model is built using TensorFlow/Keras and achieves high accuracy by preprocessing the data and optimizing the network architecture.

## Project Overview

The model is designed as a feedforward neural network with multiple layers. The steps involved in this project include:
1. **Data Preprocessing:** Loading the MNIST dataset and normalizing the data.
2. **Model Building:** Creating a neural network with one input layer, one hidden layer with ReLU activation, and an output layer.
3. **Model Training:** Training the model using the training dataset.
4. **Evaluation:** Evaluating the model’s accuracy using the test dataset and confusion matrix.

## Dataset: MNIST

- **Source:** [MNIST Handwritten Digits Database](http://yann.lecun.com/exdb/mnist/)
- **Description:** The MNIST dataset consists of 60,000 training images and 10,000 test images, where each image is a 28x28 grayscale representation of a digit (0-9).
- **Labels:** Each image is associated with a label (digit) from 0 to 9.
- **Usage:** The dataset is widely used as a benchmark for testing machine learning models on image classification tasks.


## Technologies Used
- Python
- TensorFlow/Keras
- NumPy
- Matplotlib
- Seaborn

## Steps

### 1. Data Loading & Preprocessing
The MNIST dataset is loaded and normalized using Z-Score normalization to improve accuracy.

### 2. Model Architecture
The model is designed with the following structure:
- **Input Layer:** Flattening the 28x28 pixel images into a 784-dimensional vector.
- **Hidden Layer:** A fully connected layer with Sigmoid / ReLU activation.
- **Output Layer:** 10 neurons corresponding to the digits 0-9, with a linear / softmax activation to output class probabilities.

### 3. Model Training
The model is trained using the Adam optimizer and Sparse Categorical Crossentropy loss function.

### 4. Evaluation
The accuracy of the model is evaluated using the test data, and the performance is visualized using a confusion matrix.

## Results

- **Accuracy:** The model achieves an accuracy of 99.20% on the test dataset.
- **Confusion Matrix:** Provides detailed insights into correctly and incorrectly classified digits.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.


