# loan_default

## Objective
Develop machine learning models to predict the likelihood of a borrower defaulting on a loan.

## Tech Stack
- Programming Language: Python

## Project Workflow
* Data Acquisition:
  * Source: Kaggle dataset
  * Description: The dataset includes various features related to loan applicants and their loan statuses.
* Data Preprocessing:
  * Feature Selection: Extract relevant columns pertinent to loan default prediction.
  * Data Cleaning: Handle missing values, outliers, and inconsistencies to ensure data quality.
* Feature Engineering:
  * Target Variable Transformation: Convert the loan_status feature into a binary variable:
    * 1 indicates default.
    * 0 indicates no default.
  * Feature Conversion: Transform categorical features such as term into numerical values for model compatibility.
* Model Training:
  * Logistic Regression: Serves as the baseline model for binary classification tasks.
  * Decision Tree: Provides interpretable decision rules and captures non-linear relationships.
  * Random Forest: An ensemble method that enhances predictive performance and mitigates overfitting by aggregating multiple decision trees.
* Model Evaluation:
  * Accuracy: Measures the overall correctness of the model's predictions. However, given the class imbalance in the dataset, accuracy alone may not be a sufficient metric.
  * Precision: Assesses the proportion of predicted defaults that are actual defaults, indicating the model's reliability in identifying defaulters.
  * Recall: Evaluates the proportion of actual defaults correctly identified by the model, reflecting its sensitivity.
  * F1 Score: Computes the harmonic mean of precision and recall, providing a balanced metric that is particularly useful in imbalanced datasets.
 
## Results
​Upon evaluating the models using the specified metrics, it is evident that additional fine-tuning is necessary. Despite previous adjustments, the models continue to exhibit suboptimal performance, as indicated by low precision, recall, and F1 scores. This suggests that further refinements are required to enhance their effectiveness in predicting loan defaults.

## Conclusion: 
This project demonstrates the application of various machine learning techniques to predict loan defaults, highlighting the importance of data preprocessing, feature engineering, and the selection of appropriate evaluation metrics in handling imbalanced datasets. 
