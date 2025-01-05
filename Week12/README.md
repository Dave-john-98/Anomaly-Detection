# Mortgage Probability of Default Prediction: SHAP Value Analysis

## Assignment Overview
This project focuses on using **SHAP (SHapley Additive exPlanations) values** to interpret a **Random Forest model** trained on mortgage probability of default data. The goal is to identify key predictors, explain their relationships with the target variable, and provide actionable insights based on the results.

## Dataset Description
- **Domain**: Mortgage default prediction.
- **Key Features**:
  - Top 10 features from prior Random Forest modeling.
  - Predictor variables include both numerical and categorical data (dummy encoded for categorical variables).
  - Imbalanced target variable: `default` (binary classification of mortgage default cases).

## Objectives
1. **Random Forest Model**:
   - Use top 10 features from previous Random Forest models.
   - Train a new Random Forest model in scikit-learn to compute SHAP values.
2. **SHAP Analysis**:
   - Generate the following SHAP plots:
     - **Summary Plot**: Displays global feature importance.
     - **Dependence Plot**: Highlights the relationship between individual features and the target variable.
     - **Force Plot**: Explains predictions for four individual observations.
   - Interpret the top 5 features, detailing their relationships with the target variable and economic implications.
3. **Sampling**:
   - If the dataset is large, sample 10-20% of the data for faster computations.

## Key Sections
1. **Introduction**:
   - Overview of SHAP values and their role in model interpretability.
   - Summary of dataset and modeling objectives.
2. **Model Training**:
   - Training a scikit-learn Random Forest model with the top 10 features.
   - Explanation of data preprocessing, including imputation and dummy encoding.
3. **SHAP Value Computation**:
   - Computation of SHAP values using the trained model.
   - Discussion of the computational advantages of using TreeExplainer over KernelExplainer.
4. **Visualization and Interpretation**:
   - Analysis of global feature importance using the Summary Plot.
   - Examination of individual feature impacts with Dependence and Force Plots.
5. **Insights**:
   - Business interpretation of the top 5 features.
   - Relationships between predictors and mortgage default probability.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data preprocessing.
  - `scikit-learn` for Random Forest modeling.
  - `shap` for SHAP value computation and visualization.
  - `matplotlib` and `seaborn` for additional visualizations.
- **Environment**:
  - Jupyter Notebook for structuring the analysis and documentation.

## Deliverables
- **HTML Report**: A Jupyter Notebook exported as an HTML file containing:
  - Model training and SHAP value analysis.
  - Visualizations of SHAP Summary, Dependence, and Force Plots.
- **Business Insights**:
  - Recommendations based on SHAP analysis for mortgage default prediction.

