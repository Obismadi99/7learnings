
# Weather Prediction Challenge

## Problem
Predict whether snow will occur on a given day based on historical weather data, with features like wind speed, temperature, and weather conditions.


## Solution
I used XGBoost for this binary classification task. Steps taken:

1. Data Preprocessing: Clean and prepare the data, including feature engineering (e.g., day of week), outliers detection and handling, and missing values handling.

2. Modeling: XGBoost was chosen for its performance and robustness to large datasets.

3. Evaluation: The model was evaluated with accuracy, precision, recall, F1 score and ROC curve.


## How to Run
Dependencies needed are downloaded on the notebook through pip install commands


## Technical Choices

1. XGBoost 
    Speed & Scalability: Handles large datasets efficiently.

    Regularization: Built-in L1/L2 penalties reduce overfitting without extra coding.

2. Bayesian Optimisation
    Can find good combinations of params faster than extensive grid search



## Future Improvements:
Try over-/undersampling techniques to handle the class imbalances

