# MPG Prediction with Machine Learning

This repository contains a complete end-to-end machine learning solution for predicting a car’s fuel efficiency (miles per gallon - MPG) using the **MPG dataset** available through Python's **seaborn** package. The goal is to predict the value of the target variable (MPG) based on other car attributes (predictors) using proper data analysis, preprocessing, and modeling techniques.

## Assignment Overview

The project follows the steps outlined below:

1. **Load and Inspect Dataset**  
   Open a Jupyter Notebook, load the MPG dataset, and inspect a few initial values to understand the structure.

2. **Identify Predictors and Target**  
   Analyze the dataset to determine which features will be used as predictors and which as the target variable. Discuss features that influence fuel efficiency.

3. **Descriptive Statistics**  
   Compute descriptive statistics of the dataset features, analyze their types, ranges, and completeness.

4. **Data Cleaning and Transformation**  
   - Remove rows with missing values.  
   - Drop categorical variables.  
   - Generate histograms of the features and analyze their distributions.  
   - Apply transformations to improve feature distributions (e.g., making them closer to Gaussian) and compare results.

5. **Feature Importance Analysis**  
   Evaluate which features most strongly affect MPG using correlation analysis and provide evidence-based discussion.

6. **Train-Test Split**  
   - Separate predictors and target variables.  
   - Split the dataset into 80% training and 20% testing sets (random state = 42).  
   - Plot and compare histograms of the target variable in training and testing sets.

7. **Modeling with Pipeline**  
   - Create a machine learning pipeline combining **StandardScaler** and **Linear Regression**.  
   - Evaluate performance on the test set using the following metrics:  
     - R² Score  
     - Mean Absolute Error (MAE)  
     - Mean Absolute Percentage Error (MAPE)  
     - Mean Squared Error (MSE)  
   - Plot Actual vs Predicted MPG values and comment on the results.

8. **Cross-Validation**  
   Perform 10-fold cross-validation, compute the mean and standard deviation of R² scores, and compare with the test set performance.

## Requirements

- Python 3.x  
- Jupyter Notebook  
- Libraries: `pandas`, `numpy`, `seaborn`, `matplotlib`, `scikit-learn`

## How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/<your-username>/MPG-Prediction.git

2. Open the Jupyter Notebook:

jupyter notebook MPG_Prediction.ipynb

3. Follow the steps in the notebook to explore, clean, and model the dataset.

## Outcome

This project demonstrates a full workflow for predictive modeling, including data cleaning, visualization, feature analysis, model training, evaluation, and cross-validation, applied to predicting car fuel efficiency.
