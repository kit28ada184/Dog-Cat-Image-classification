# Dog-Cat Image Classification Using CNN

## Project Overview
This project implements a Convolutional Neural Network (CNN) to classify images as cats or dogs using Python and TensorFlow/Keras.

## Implementation

### 1. Import Libraries
Import the required libraries, including TensorFlow, NumPy, Matplotlib, and tools for loading and processing images.

### 2. Load the Dataset
Load the training, validation, and testing images from the dataset. The images are organized into the required format for model training.

### 3. Preprocess Images
Resize the images to a fixed size and normalize pixel values to help the model learn efficiently.

### 4. Build the CNN Model
Create a CNN model with three convolutional layers. Use ReLU activation, pooling layers, and fully connected layers to extract image features and classify the images.

### 5. Compile the Model
Compile the model using the Adam optimizer, binary cross-entropy loss, and accuracy as the evaluation metric.

### 6. Train the Model
Train the CNN using the training dataset and validate its performance using the validation dataset.

### 7. Evaluate the Model
Evaluate the trained model using test images. Display training and validation accuracy and loss graphs to understand model performance.

### 8. Predict Images
Provide a new image to the trained model and predict whether it contains a cat or a dog.

## Technologies Used
- Python
- TensorFlow and Keras
- NumPy
- Matplotlib
- Google Colab

## How to Run
1. Open `workshop_project.ipynb` in Google Colab.
2. Download and extract the dataset.
3. Run the notebook cells in order.
4. Train and evaluate the CNN model.
5. Test the model with cat and dog images.

## Conclusion
This implementation demonstrates how a three-layer CNN can learn image features and classify cat and dog images. The model's performance can be evaluated using accuracy and loss metrics.
