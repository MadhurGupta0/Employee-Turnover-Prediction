# Employee Turnover Prediction

This project aims to predict employee turnover using machine learning models. We compare the performance of Logistic Regression and Random Forest classifiers on a hypothetical dataset.

## Table of Contents
- Introduction
- Installation
- Usage
- Models and Evaluation
- Dependencies
- Results
- Model Download

## Introduction
Employee turnover prediction is crucial for organizations to retain talent and reduce costs associated with hiring and training new employees. This project uses machine learning techniques to predict whether an employee will leave the company based on various features.

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/MadhurGupta0/employee-turnover-prediction.git
   cd employee-turnover-prediction
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt

## Usage
1. Run the script to train the models and evaluate their performance.
2. The script will output the accuracy and classification report for both Logistic Regression and Random Forest models.

## Models and Evaluation
### Logistic Regression
- Trained using the LogisticRegression class from sklearn.linear_model.
- Evaluated using accuracy score and classification report.
### Random Forest
- Trained using the RandomForestClassifier class from sklearn.ensemble.
- Evaluated using accuracy score and classification report.

  
## Dependencies
- pandas
- numpy
- scikit-learn
- matplotlib
- joblib

## Results
The results of the model evaluations will be displayed in the console, including accuracy scores and classification reports. Additionally, a bar chart comparing the accuracy of both models will be generated.

## Model Download
You can directly download the Employee Turnover model (employee_turnover_model.joblib) to use the model for predictions without retraining. Simply load the model using joblib:

```Python

import joblib

# Load the model
model = joblib.load('employee_turnover_model.joblib')

# Use the model for predictions
predictions = model.predict(X_test)
```


   
