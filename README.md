# AI & ML Course - Task 8: Neural Network Basics with Keras

## Overview
This repository contains the solution for Task 8. A simple Artificial Neural Network is built using TensorFlow/Keras with 2 hidden layers to perform binary classification.

## Files Included
- Task8_NN_Keras.ipynb: Complete Colab notebook. The notebook generates its own dummy CoreTech dataset internally, so no separate CSV file is needed.

## Implementation Details
1.  *Dataset:* Dummy dataset generated in-code with features: budget, duration_days, team_size. Target: project_success 0 or 1.
2.  *Preprocessing:* Train-test split and StandardScaler for feature scaling.
3.  *Model Architecture:*
    - Hidden Layer 1: 16 neurons, ReLU activation
    - Hidden Layer 2: 8 neurons, ReLU activation 
    - Output Layer: 1 neuron, Sigmoid activation
4.  *Training:* Compiled with Adam optimizer and binary_crossentropy loss. Trained for 50 epochs.
5.  *Visualization:* Training vs Validation Accuracy and Loss curves plotted.
6.  *Comparison:* Results compared with a traditional LogisticRegression model from Task 5.

## Results
- *Neural Network Test Accuracy:* [Run the .ipynb and paste your % here]
- *Logistic Regression Test Accuracy:* [Run the .ipynb and paste your % here]

## How to Run
1.  Open Task8_NN_Keras.ipynb in Google Colab.
2.  Run all cells. No external data upload required.

## Tech Stack
Python, TensorFlow/Keras, Scikit-learn, Pandas, Matplotlib
