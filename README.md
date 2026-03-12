# Handwritten Digit Recognition using CNN

## Overview
This project builds a Convolutional Neural Network (CNN) model to recognize handwritten digits from images. The model is trained on the MNIST dataset and can classify digits from 0 to 9.

Handwritten digit recognition is a common computer vision task and is widely used in applications such as automated form processing, bank check recognition, and document digitization.

---

## Dataset
The model is trained using the **MNIST dataset**, which contains:

- 70,000 grayscale images
- Image size: 28 x 28 pixels
- 10 classes (digits 0–9)

Dataset split:
- Training set: 60,000 images
- Test set: 10,000 images

---

## Technologies Used

- Python  
- TensorFlow / Keras  
- NumPy  
- Matplotlib  

---

## Model Architecture

The Convolutional Neural Network (CNN) includes:

- Convolutional Layers for feature extraction
- Max Pooling Layers for dimensionality reduction
- Fully Connected Dense Layers for classification
- Softmax activation function for predicting digit classes

---

## Training Process

1. Load and preprocess the MNIST dataset  
2. Normalize image pixel values  
3. Build the CNN architecture  
4. Train the model on training data  
5. Evaluate performance on the test dataset  

---

## Results

- Test Accuracy: ~98%

The model performs well in recognizing handwritten digits with high accuracy.

---

## Applications

- Automatic form reading
- Bank check digit recognition
- Digitizing handwritten documents

---

## Author

Nguyen Van Dung  
Data Science Student  
University of Da Lat
Vietnam
