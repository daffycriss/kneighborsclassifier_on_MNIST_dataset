# MNIST Binary Classification: Odd vs Even

This repository contains a machine learning project that works with the **MNIST dataset** to classify handwritten digits as **odd** or **even** numbers. The project demonstrates data preprocessing, model training, hyperparameter tuning, evaluation, and visualization.

## Assignment Overview

The project follows these steps:

1. **Load and Normalize Data**  
   - Load the MNIST dataset and split it into training (60,000 images) and test sets (10,000 images).  
   - Normalize pixel values to a range of 0 to 1.

2. **Binary Classification Setup**  
   Convert the original 10-class problem into a binary classification task:  
   - Odd digits → class 1  
   - Even digits (including 0) → class 0

3. **K-Nearest Neighbors Model & Hyperparameter Tuning**  
   - Use `KNeighborsClassifier` for classification.  
   - Perform grid search on `n_neighbors` with values `[3, 5, 7]` to find the optimal hyperparameters.

4. **Model Evaluation**  
   - Evaluate the model on the test set using **accuracy**, **precision**, and **recall**.  
   - Apply 3-fold cross-validation for robust performance estimation.

5. **Confusion Matrix Analysis**  
   - Compute the confusion matrix on the training set.  
   - Identify how many samples were misclassified as odd or even.

6. **ROC Curve and AUC**  
   - Plot the **ROC curve** to visualize classification performance.  
   - Calculate the **Area Under the Curve (AUC)** to quantify model discrimination.

## Requirements

- Python 3.x  
- Libraries: `numpy`, `pandas`, `matplotlib`, `scikit-learn`, `tensorflow` or `keras` (for MNIST loading)

## How to Run

1. Clone the repository:  
   ```bash
   git clone https://github.com/daffycriss/kneighborsclassifier_on_MNIST_dataset.git

2. Open the Jupyter Notebook:
   jupyter notebook MNIST_Binary_Classification.ipynb

3. Follow the notebook to load data, train the KNN model, tune hyperparameters, and evaluate performance.

## Outcome

This project provides a complete workflow for binary image classification, including preprocessing, KNN modeling, hyperparameter tuning, cross-validation, performance metrics, confusion matrix analysis, and ROC/AUC evaluation.
