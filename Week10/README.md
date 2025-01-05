# Mortgage Probability of Default Prediction Using GBM and Deep Learning

## Assignment Overview
This project involves predicting the **probability of mortgage default** using two machine learning models:
1. **Gradient Boosting Machine (GBM)**
2. **Deep Learning Model**

The analysis includes hyperparameter tuning for both models to optimize performance and improve precision. Class imbalance is addressed using the `balance_classes` parameter, and model evaluation is conducted using **ROC**, **Cumulative Lift**, and **Precision-Recall** metrics.

## Dataset Description
- **Domain**: Mortgage default prediction.
- **Key Features**:
  - Credit scores, loan amounts, payment history, and other mortgage-related attributes.
  - Encoded categorical variables for compatibility with machine learning models.
  - Imbalanced target variable: `default` (binary classification of mortgage default cases).

## Objectives
1. **Model Development**:
   - Build and tune either **GBM** or **XGBoost** for predicting mortgage defaults.
   - Implement a **Deep Learning** model for the same task.
2. **Hyperparameter Tuning**:
   - Conduct grid search to optimize hyperparameters for both models.
   - Experiment with the `balance_classes` parameter to handle class imbalance.
3. **Performance Evaluation**:
   - Assess model performance using ROC, Cumulative Lift, and Precision-Recall metrics.
4. **Feature Selection**:
   - Select or drop variables as necessary to improve model predictability and reduce noise.

## Key Sections
1. **Introduction**:
   - Overview of the dataset, objectives, and challenges (e.g., class imbalance).
2. **Model Descriptions**:
   - Explanation of GBM/XGBoost and Deep Learning approaches.
   - Justification for their use in mortgage default prediction.
3. **Hyperparameter Tuning**:
   - Detailed steps for grid search and parameter selection.
   - Exploration of the impact of the `balance_classes` parameter.
4. **Model Evaluation**:
   - Comparison of models using ROC, Cumulative Lift, and Precision-Recall metrics.
5. **Insights**:
   - Business implications of the results.
   - Recommendations for real-world applications of the models.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `h2o` for GBM, XGBoost, and Deep Learning implementations.
  - `scikit-learn` for evaluation metrics.
  - `matplotlib` and `seaborn` for visualization.
- **Environment**:
  - Jupyter Notebook for structuring the analysis and documentation.

## Deliverables
- **HTML Report**: A Jupyter Notebook exported as an HTML file containing:
  - Model building, hyperparameter tuning, and evaluation results.
  - Visualizations of performance metrics and results.
- **Business Insights**:
  - Interpretations of model outputs and actionable recommendations.

