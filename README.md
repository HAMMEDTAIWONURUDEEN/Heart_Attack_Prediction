# Heart_Attack_prediction
# Heart Attack Prediction Using Machine Learning

## Project Overview
This project focuses on developing a machine learning classification model to predict heart attack outcomes using patient-related medical measurements.

The objective is to explore how machine learning algorithms can identify patterns in medical data and classify records into positive and negative outcomes.

## Dataset Description
The dataset contains patient-related features, including medical measurements used to train and evaluate the classification models.

**Target Variable:**
- `0` – Negative
- `1` – Positive

## Data Preprocessing
The project involved preparing the dataset for machine learning, including:
- Separating features and target variables.
- Splitting the dataset into training, validation, and testing sets.
- Applying appropriate preprocessing techniques.
- Using cross-validation during hyperparameter tuning.

## Algorithms Used
1. Logistic Regression
2. Random Forest Classifier

## Hyperparameter Optimization
GridSearchCV was used to identify suitable Random Forest hyperparameters.

The optimization process involved:
- Number of estimators.
- Maximum tree depth.
- Minimum samples required to split a node.
- Minimum samples required at a leaf node.

Five-fold Stratified Cross-Validation was used during the search.

## Model Performance

The Random Forest model achieved the following results on the test split:

| Evaluation Metric | Result |
|---|---:|
| Accuracy | 98.48% |
| Precision (Class 0) | 98.68% |
| Recall (Class 0) | 97.40% |
| Precision (Class 1) | 98.36% |
| Recall (Class 1) | 99.17% |

**Confusion Matrix:**
- True Negatives: 75
- False Positives: 2
- False Negatives: 1
- True Positives: 120

## Technologies and Libraries
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Key Learning Outcomes
Through this project, I gained practical experience in:
- Data preprocessing and exploratory data analysis.
- Classification algorithms.
- Random Forest modelling.
- Hyperparameter tuning with GridSearchCV.
- Cross-validation.
- Model evaluation using accuracy, precision, recall, F1-score, and confusion matrices.
- Prediction using `predict()` and `predict_proba()`.

## Disclaimer
This project is strictly for educational and machine learning practice. It is not a clinically validated medical diagnostic system and should not be used to make medical decisions.

## Author
Mechatronics Engineering Student | Machine Learning Enthusiast
