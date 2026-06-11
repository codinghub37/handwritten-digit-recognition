# Handwritten Digits Recognition Using Neural Network

## Project Overview

This project implements a Deep Neural Network using TensorFlow and Keras to recognize handwritten digits from the MNIST dataset. The model is trained on thousands of labeled digit images and learns to classify handwritten digits from 0 to 9 with high accuracy.

The project demonstrates the practical application of Artificial Intelligence, Machine Learning, and Deep Learning techniques for image classification tasks.

---

## Problem Statement

Handwritten digit recognition is a fundamental problem in computer vision and machine learning. The objective of this project is to build a neural network capable of accurately identifying handwritten digits from image data.

---

## Dataset

The project uses the MNIST Handwritten Digits Dataset.

### Dataset Details

* 60,000 training images
* 10,000 testing images
* Grayscale images
* Image size: 28 × 28 pixels
* Digit classes: 0–9

---

## Technologies Used

* Python
* TensorFlow
* Keras
* NumPy
* Matplotlib
* Jupyter Notebook

---

## Project Workflow

### 1. Import Required Libraries

The necessary libraries such as TensorFlow, NumPy, and Matplotlib are imported.

### 2. Load Dataset

The MNIST dataset is loaded directly from TensorFlow.

### 3. Data Preprocessing

The dataset is prepared for training by:

* Normalizing pixel values
* Converting image data into a suitable format
* Splitting data into training and testing sets

### 4. Build Neural Network

A Sequential Neural Network model is created using:

* Input Layer
* Hidden Dense Layers
* ReLU Activation Function
* Output Layer with Softmax Activation

### 5. Train the Model

The neural network is trained using the MNIST training dataset.

### 6. Evaluate the Model

Model performance is evaluated using the testing dataset.

### 7. Make Predictions

The trained model predicts handwritten digits from unseen images.

### 8. Visualize Results

Predictions and sample images are visualized using Matplotlib.

---

## Neural Network Architecture

### Input Layer

* 784 Neurons (28 × 28 image flattened)

### Hidden Layer

* Dense Layer
* ReLU Activation Function

### Output Layer

* 10 Neurons
* Softmax Activation Function

---

## Features

* Handwritten Digit Classification
* Deep Learning Implementation
* TensorFlow/Keras Based Model
* Data Visualization
* Model Training and Evaluation
* Prediction on Test Images
* MNIST Dataset Integration

---

## Installation

Clone the repository:

```bash
git clone https://github.com/yourusername/digits-recognition-neural-network.git
```

Move to the project directory:

```bash
cd digits-recognition-neural-network
```

Install required dependencies:

```bash
pip install -r requirements.txt
```

---

## Running the Project

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```bash
digits_recognition_neural_network.ipynb
```

Run all notebook cells sequentially.

---

## Results

The neural network successfully classifies handwritten digits and achieves high accuracy on the MNIST test dataset.

---

## Future Improvements

* Implement Convolutional Neural Networks (CNN)
* Improve model accuracy
* Real-time digit recognition
* Custom image prediction support
* Web deployment using Flask or Streamlit

---

## Learning Outcomes

This project helped in understanding:

* Artificial Intelligence
* Machine Learning
* Deep Learning
* Neural Networks
* Image Classification
* TensorFlow Framework
* Data Preprocessing
* Model Evaluation Techniques

