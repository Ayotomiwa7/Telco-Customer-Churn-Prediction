# Telco-Customer-Churn-Prediction
### Model Prediction on Telco Customer Churn

This repository contains code for predicting customer churn in a telco dataset using various machine learning models. We explored five different models: Logistic Regression, Random Forest, Decision Tree, Support Vector Machine (SVM), and K-Nearest Neighbors (KNN). For each model, we conducted experiments both with tuned parameters and default parameters to assess their performance.

#### Methodology:
1. Data Wrangling and Preprocessing
2. Model Development and Evaluation
3. Handling Class Imbalance (with SMOTEENN)
4. Model Saving

#### Dataset Used:
The dataset used for this project contains information about telco customers obtained from Kaggle

#### Usage:
To replicate the experiments or apply the trained model:
1. Obtain a similar telco customer dataset.
2. Follow the provided Jupyter notebooks or Python scripts for data preprocessing, model training, and evaluation.
3. Adjust parameters or algorithms as needed based on the specifics of your dataset.
4. Apply the SMOTEENN technique with Random Forest classifier for handling class imbalance.
5. Save the trained model using the provided code snippet with `pickle`.
6. Utilize the saved model for making predictions on new data.

#### Dependencies:
- Python 3
- Libraries: NumPy, pandas, scikit-learn, imbalanced-learn, pickle
