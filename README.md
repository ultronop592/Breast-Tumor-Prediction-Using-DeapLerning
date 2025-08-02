#Breast Cancer Detection Using Neural Network
This project uses a deep learning model to classify breast cancer tumors as benign (non-cancerous) or malignant (cancerous) based on medical features. The model is trained and evaluated on the Breast Cancer Wisconsin dataset using a neural network implemented in TensorFlow/Keras.

#Dataset
Source: sklearn.datasets.load_breast_cancer()

Classes:

0 → Malignant

1 → Benign

Features: 30 numeric features describing characteristics of cell nuclei in breast cancer biopsies.

# Project Workflow
Data Loading & Exploration

Load data using Scikit-learn

Check for missing values

Summary statistics and label distribution

Data Preprocessing
Feature-target separation

Train-test split (80:20 ratio)

Feature standardization using StandardScaler

Model Building

Sequential neural network with:

Flatten layer for input

Dense hidden layer with ReLU

Dropout for regularization

Output layer with sigmoid activation (2 neurons for 2 classes)

Model Compilation

Optimizer: Adam

Loss function: SparseCategoricalCrossentropy

Metric: Accuracy

Training & Evaluation

Train for 10 epochs with validation split

Plot accuracy and loss curves

Evaluate on test data

#Results
Achieved a test accuracy of ~96%

Model successfully predicts whether a tumor is benign or malignant

# Visualizations
Training vs Validation Accuracy

Training vs Validation Loss
(Displayed using Matplotlib)
