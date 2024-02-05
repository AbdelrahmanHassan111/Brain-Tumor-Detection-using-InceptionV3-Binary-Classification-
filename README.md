# Brain Tumor Detection with InceptionV3

**Note: This repository is currently read-only and not open for modifications. If you have any inquiries or suggestions, feel free to contact the project owner.**

Welcome to the Brain Tumor Detection project using the InceptionV3 convolutional neural network architecture. This repository offers a comprehensive solution for brain tumor detection, encompassing both training and testing scripts. Explore the detailed information below to understand and utilize the full potential of this project.

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

## 3. Additional Information:

### 3.1 GUI Application:

...

### 3.2 Contribution and Support:

Feel free to contribute to the project, customize it for your needs, or report any issues. Open an issue or pull request for questions, improvements, or collaboration.

### 3.3 License:

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code in accordance with the terms of the license.

## 4. Installation:

### 4.1 Bash Script:

To install the required dependencies, you can use the following bash script:

```bash
# Clone the repository
git clone https://github.com/AbdelrahmanHassan111/Brain-Tumor-Detection-using-InceptionV3.git

# Move to the project directory
cd Brain-Tumor-Detection-using-InceptionV3

# Create a virtual environment (optional but recommended)
python -m venv venv

# Activate the virtual environment
source venv/bin/activate  # On Windows, use 'venv\Scripts\activate'

# Install dependencies
pip install -r requirements.txt
![output](https://github.com/AbdelrahmanHassan111/Brain-Tumor-Detection-using-InceptionV3/assets/156480367/4c62b497-ac4a-404c-8689-bddd0dce1ed4)
