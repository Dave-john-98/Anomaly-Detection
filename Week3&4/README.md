# Exploratory Data Analysis and Logistic Regression Assignment

## Description

This assignment involves conducting an in-depth Exploratory Data Analysis (EDA), applying feature engineering techniques, and building a predictive model to analyze loan default behavior. The target variable is `loan_default`, and the dataset contains a mix of categorical and continuous variables. The goal is to understand the relationship between predictors (X) and the target variable (Y) and to evaluate the model's performance using ROC curves and a gains table.

## Objectives

1. **Takeaways from the Assigned Article:**
   - Summarized ideas from the article to inform EDA and feature engineering.
   - Applied insights into structuring the analysis and identifying key data transformations.

2. **Exploratory Data Analysis (EDA):**
   - Analyzed the distribution of the target variable (`loan_default`) against each predictor.
   - Focused on understanding how predictor variables influence the likelihood of loan default.
   - Variables analyzed include:
     - **Categorical Variables:** `AP001`, `AP003`, `AP008`, `CR015`, `CR019`, `PA022`, `PA023`, `TD001`, `TD005`, `TD006`, `TD009`, `TD010`, `TD014`
     - **Continuous Variables:** `CR009`, `PA029`

3. **Feature Engineering:**
   - Applied Weight-of-Evidence (WOE) transformations for categorical variables to improve model interpretability.
   - Created transformed features with enhanced predictive power for logistic regression.

4. **Model Building:**
   - Developed a logistic regression model to predict loan defaults.
   - Split the data into training and testing sets to ensure robust evaluation.
   - Assessed the model's performance using:
     - Receiver Operating Characteristic (ROC) curve
     - Gains table and lift analysis.

5. **Documentation:**
   - Structured the analysis with sub-sections for each variable or group of variables.
   - Summarized insights and feature contributions at the end of each sub-section.

## Methods and Tools

- **Tools Used:**
  - Python for data analysis and modeling.
  - Libraries: `Pandas`, `Seaborn`, `Matplotlib`, `Scikit-learn` for logistic regression.
  
- **Techniques:**
  - Visualization of data distributions and relationships.
  - Application of Weight-of-Evidence (WOE) encoding.
  - Model evaluation with standard performance metrics.

## Results and Insights

- **EDA Insights:**
  - Provided detailed relationships between each variable and loan defaults.
  - Highlighted significant predictors that influenced loan default rates.

- **Model Performance:**
  - WOE-transformed features improved model interpretability and performance.
  - Achieved better discrimination of loan defaults using the ROC and lift analysis.

## Deliverables

- **Final Submission:** An HTML report containing:
  - EDA visualizations and insights.
  - Feature engineering transformations.
  - Logistic regression results with performance evaluation.
  - Conclusions drawn from the gains table and lift analysis.

## Conclusion

This assignment demonstrated the importance of high-quality feature engineering and thorough EDA in predictive modeling. The use of WOE encoding and structured analysis provided a robust foundation for the logistic regression model, which successfully predicted loan defaults with meaningful insights.
