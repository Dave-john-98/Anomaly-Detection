# Mortgage Probability of Default Prediction Using GLM and AutoML

## Assignment Overview
This project involves predicting the **probability of mortgage default** using two machine learning approaches:
1. **Generalized Linear Model (GLM)** with hyperparameter tuning.
2. **AutoML** for automated model selection and optimization.

The analysis focuses on optimizing model performance through grid search for GLM and leveraging H2O's AutoML for a robust comparison. Key performance metrics include **ROC**, **Cumulative Lift**, and **Precision-Recall**.

## Dataset Description
- **Domain**: Mortgage default prediction.
- **Key Features**:
  - Mortgage-specific attributes, such as credit scores, loan amounts, and payment history.
  - Predictor variables encoded for compatibility with machine learning models.
  - Imbalanced target variable: `default` (binary classification of mortgage default cases).

## Objectives
1. **GLM Model**:
   - Implement and fine-tune a Generalized Linear Model.
   - Perform hyperparameter tuning for key parameters like `alpha` and `lambda` to optimize performance.
2. **AutoML**:
   - Utilize H2O's AutoML for automated model selection and tuning.
   - Compare the results with the manually tuned GLM model.
3. **Performance Evaluation**:
   - Evaluate both models using ROC, Cumulative Lift, and Precision-Recall metrics.
   - Compare the precision improvements achieved through hyperparameter tuning.
4. **Feature Selection**:
   - Experiment with selecting or dropping variables to improve model predictability.

## Key Sections
1. **Introduction**:
   - Overview of the dataset, objectives, and challenges.
2. **GLM Implementation**:
   - Steps to build and tune the GLM model.
   - Grid search for `alpha` and `lambda` parameters.
   - Insights from the model performance metrics.
3. **AutoML Analysis**:
   - Application of H2O's AutoML for automated model training.
   - Performance comparison with the GLM model.
4. **Insights**:
   - Analysis of key findings and business implications.
   - Recommendations for deploying the models in real-world scenarios.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data preprocessing.
  - `h2o` for GLM and AutoML implementations.
  - `scikit-learn` for evaluation metrics.
  - `matplotlib` and `seaborn` for visualization.
- **Environment**:
  - Jupyter Notebook for structured analysis and documentation.

## Deliverables
- **HTML Report**: A Jupyter Notebook exported as an HTML file, including:
  - Model building, hyperparameter tuning, and evaluation results.
  - Visualizations of model performance and metrics.
- **Business Insights**:
  - Recommendations based on model outputs for mortgage default prediction.


