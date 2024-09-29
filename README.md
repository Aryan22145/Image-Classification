# Image Classification Project

## Project Overview
This project classifies images of handwritten digits using a Convolutional Neural Network (CNN) model built with TensorFlow. The main objective is to leverage deep learning techniques to achieve high classification accuracy on the MNIST dataset, which contains 70,000 grayscale images of digits (0-9).

## Features
- **Data Preprocessing**: 
  - Normalization: Scales pixel values to a range of 0 to 1 for improved convergence during training.
  - Reshaping: Adjusts the dimensions of the input images to fit the model's expected input shape.
  - Data Augmentation: Applies random transformations (like rotation and shifting) to enhance model generalization.
  
- **Convolutional Neural Networks (CNN)**: 
  - **Architecture**: 
    - Convolutional layers for feature extraction.
    - Max pooling layers to reduce dimensionality.
    - Fully connected layers for classification.
  
- **TensorFlow and Keras**: 
  - Utilizes TensorFlow as the backend and Keras as the high-level API for building, training, and evaluating the model.
  
- **Model Evaluation and Visualization**: 
  - Accuracy and loss metrics are plotted to assess model performance.
  - Confusion matrix is generated to visualize prediction accuracy across different classes.
  - Sample predictions are displayed alongside the true labels.

## Installation
To set up the project, follow these steps:

 1.**Clone the Repository**:
   ```bash
   git clone https://github.com/Aryan22145/Image-Classification.git
```
2.**Change the Directory**:
```bash
cd Image-Classification
```
3.**IInstall Dependencies**:
```bash 
pip install -r requirements.txt
```
4.**Run the Jupyter Notebook**:
```bash
jupyter notebook MNIST.ipynb
```
## Results
  The model achieved an accuracy of over 99% on the MNIST dataset, indicating its effectiveness in recognizing handwritten digits. The following metrics were observed:

**Training Accuracy: 99.5%**
**Validation Accuracy: 99.2%**
**Test Accuracy: 99.1%**
## License
This project is licensed under Apache
