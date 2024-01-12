# Brain Tumor Detection with InceptionV3

**Note: This repository is currently read-only and not open for modifications. If you have any inquiries or suggestions, feel free to contact the project owner.**

Welcome to the Brain Tumor Detection project using the InceptionV3 convolutional neural network architecture. This repository offers a comprehensive solution for brain tumor detection, encompassing both training and testing scripts. Explore the detailed information below to understand and utilize the full potential of this project.

## 1. Training Code:

### 1.1 Overview:

The `train_brain_tumor_model.py` script orchestrates the entire training process. Leveraging the InceptionV3 model with pre-trained ImageNet weights, it customizes the architecture for binary classification, distinguishing between the presence and absence of brain tumors. The script utilizes the Kaggle MRI Brain Tumor dataset, applying advanced data augmentation techniques to enhance the model's generalization capabilities. Upon completion, the final trained model is saved as 'brain_tumor_trained_model.h5'.

### 1.2 Dependencies:

Ensure you have the following dependencies installed:

- `keras`
- `tensorflow`
- `numpy`
- `PIL`
- `tkinter`

### 1.3 Usage:

1. Modify the script to specify the paths for training data (`train_data_dir`) and validation data (`validation_data_dir`).
2. Install the required dependencies.
3. Execute the script to initiate the model training process.
4. Save and load the trained model weights for future use.

## 2. Testing Code:

### 2.1 Overview:

The `test_brain_tumor_model.py` script handles the post-training phase. It loads the pre-trained model and provides a user-friendly graphical interface for testing predictions. The script supports both single image prediction and folder analysis, displaying results interactively. Additionally, it generates a testing accuracy plot to facilitate a comprehensive evaluation of the model's performance.

### 2.2 Dependencies (for Testing):

Ensure you have the following dependencies installed for testing:

- `tensorflow`
- `numpy`
- `tkinter`
- `PIL`
- `matplotlib`

### 2.3 Dataset:

The brain tumor dataset used for both training and testing is sourced from Kaggle's MRI Brain Tumor dataset. Make sure you have the necessary permissions to use and distribute this dataset.

### 2.4 Usage:

1. Confirm that the testing dependencies are installed.
2. Load the pre-trained model using 'brain_tumor_trained_model.h5'.
3. Run the testing script and use the graphical user interface to select either a single image or a folder for evaluation.

## 3. Additional Information:

### 3.1 GUI Application:

For a more user-friendly and interactive testing experience, the `main_gui.py` script provides a graphical user interface. Users can explore the model's predictions on various images through this intuitive interface.

### 3.2 Contribution and Support:

Feel free to contribute to the project, customize it according to your needs, or report any issues. Open an issue or submit a pull request for questions, improvements, or collaborative efforts.

### 3.3 License:

This project is licensed under the [MIT License](LICENSE). Feel free to use, modify, and distribute the code in accordance with the terms of the license.

---

**Note:** This repository is read-only, and modifications are not currently allowed. If you have any inquiries or suggestions, please contact the project owner.

**Note:** Ensure that you replace `https://github.com/AbdelrahmanHassan111/Brain-Tumor-Detection-using-InceptionV3.git` with the actual link to your GitHub repository. Customize the content further based on your project's specific details and structure.
