# Brain Tumor Detection with InceptionV3

This repository contains a comprehensive implementation for brain tumor detection using the InceptionV3 convolutional neural network architecture. The project consists of both training and testing scripts, providing users with a complete solution for building, training, and evaluating a brain tumor detection model.

## 1. Training Code:

### 1.1 Overview:

The training script, `train_brain_tumor_model.py`, utilizes the InceptionV3 model with pre-trained ImageNet weights. It customizes the model for binary classification, distinguishing between brain tumor presence and absence. The training is performed on a Kaggle MRI Brain Tumor dataset, incorporating data augmentation techniques for enhanced model generalization. The final trained model is saved to 'brain_tumor_trained_model.h5'.

### 1.2 Dependencies:

- `keras`
- `tensorflow`
- `numpy`
- `PIL`
- `tkinter`

### 1.3 Usage:

1. Replace the paths in the script for training data (`train_data_dir`) and validation data (`validation_data_dir`).
2. Ensure the required dependencies are installed.
3. Execute the script to train the model.
4. Save and load the trained model weights for future use.

## 2. Testing Code:

### 2.1 Overview:

The testing script, `test_brain_tumor_model.py`, loads the pre-trained model and provides a user-friendly graphical interface for testing predictions. It supports both single image prediction and folder analysis, displaying results interactively. A testing accuracy plot is generated, aiding in the evaluation of model performance.

### 2.2 Dependencies (for Testing):

- `tensorflow`
- `numpy`
- `tkinter`
- `PIL`
- `matplotlib`

### 2.3 Dataset:

The brain tumor dataset used for training and testing is sourced from Kaggle's MRI Brain Tumor dataset. Ensure you have the necessary permissions to use and distribute this dataset.

### 2.4 Usage:

1. Ensure the dependencies are installed.
2. Load the pre-trained model using 'brain_tumor_trained_model.h5'.
3. Run the testing script and use the GUI to select either a single image or a folder for evaluation.

## 3. Contribution and Support:

Feel free to contribute to the project, customize it for your needs, or report any issues. Open an issue or pull request for questions, improvements, or collaboration.

