# Breast Cancer Classification using Neural Networks

## Overview
This project focuses on the classification of breast cancer tumors as malignant or benign based on various features. The dataset used for this project is 'Breast_cancer_data.csv,' containing information about the mean radius, mean texture, mean perimeter, mean area, and mean smoothness of breast tumors, along with their diagnosis (0 for benign and 1 for malignant).

## Dataset
- The dataset contains 569 entries with 6 columns.
- Descriptive statistics reveal key insights into the distribution of features for both benign and malignant tumors.

## Data Preprocessing and Visualization
- The 'diagnosis' column was separated from the dataset and stored in 'y'.
- The feature data was normalized using TensorFlow's `Normalization` layer.
- Histograms and a violin plot were used to visualize the distribution of features and diagnoses.

## Machine Learning Model
- A Sequential Neural Network model was implemented using TensorFlow's Keras.
- The model consists of two Dense layers with ReLU activation in the hidden layer and a sigmoid activation in the output layer.
- Binary crossentropy loss and the Adamax optimizer were used for model compilation.
- The model was trained on the training data for 15 epochs with a batch size of 43.

## Model Evaluation
- The model was evaluated on the test set, achieving an accuracy of approximately 93.71%.
- The test loss was 0.1281.

## Future Steps
- Further fine-tuning of hyperparameters and model architecture.
- Exploration of additional evaluation metrics and visualization techniques.
- Consideration of more advanced neural network architectures.
