# Mortgage Probability of Default Analysis Using Random Forest and Sampling Techniques

## Assignment Overview
This project involves building a **Random Forest (RF) model** to predict the probability of mortgage defaults. The analysis includes experimenting with at least two sampling techniques (under-sampling and over-sampling) to address class imbalance in the dataset. Performance metrics such as **ROC (Receiver Operating Characteristic)** and **Cumulative Lift** are used to evaluate and compare the model results.

## Dataset Description
- **Domain**: Mortgage default prediction.
- **Key Features**:
  - Mortgage-specific attributes such as credit scores, loan amounts, and payment history.
  - Predictor variables encoded from categorical features for model compatibility.
  - Highly imbalanced target variable: `default` (binary classification of mortgage default cases).

## Objectives
1. **Random Forest Model**:
   - Build a robust Random Forest model using hyperparameter tuning.
   - Evaluate model performance using ROC and Cumulative Lift metrics.
2. **Sampling Techniques**:
   - Apply **Over-Sampling** (e.g., SMOTE or Random Over-Sampling) to increase the representation of the minority class.
   - Apply **Under-Sampling** to balance the dataset by reducing the majority class samples.
   - Compare the effectiveness of the sampling techniques in improving model performance.
3. **Feature Selection**:
   - Experiment with variable selection/dropping to enhance model predictability.
4. **Hyperparameter Tuning**:
   - Test a range of hyperparameters to optimize the Random Forest model.
   - Present the final hyperparameters that deliver the best outcome.

## Key Sections
1. **Introduction**:
   - Overview of the dataset, objectives, and class imbalance challenge.
2. **Random Forest Model**:
   - Detailed steps for building and tuning the Random Forest classifier.
   - Use of Python’s `scikit-learn` or H2O library for implementation.
3. **Sampling Techniques**:
   - Description and application of under-sampling and over-sampling methods.
   - Comparison of results with and without sampling.
4. **Performance Evaluation**:
   - Use of ROC and Cumulative Lift metrics to measure model effectiveness.
   - Analysis of model precision and predictability improvements.
5. **Insights and Recommendations**:
   - Business interpretation of results and actionable recommendations.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data preprocessing and manipulation.
  - `scikit-learn` for model building and evaluation.
  - `imblearn` for over-sampling and under-sampling techniques.
  - H2O framework for hyperparameter tuning and advanced modeling.
- **Environment**:
  - Jupyter Notebook for structured analysis and documentation.

## Deliverables
- **HTML Report**: A Jupyter Notebook exported as an HTML file containing:
  - Random Forest model building and evaluation.
  - Sampling techniques and their impact on model performance.
  - Visualizations and insights derived from the analysis.
