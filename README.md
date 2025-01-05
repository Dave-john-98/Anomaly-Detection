# Anomaly Detection: Course Summary and Assignments

## Course Overview
This course focuses on **Anomaly Detection** using a variety of techniques in supervised and unsupervised learning. It emphasizes the importance of identifying outliers, understanding feature relationships, and applying machine learning algorithms to detect anomalies in real-world datasets. The assignments covered a range of topics, from exploratory data analysis (EDA) to advanced machine learning models, with a focus on practical implementation, interpretability, and deriving actionable insights.

## Topics Covered
1. **Exploratory Data Analysis (EDA)**:
   - Conducted detailed EDA to uncover patterns, trends, and potential anomalies.
   - Built new features to enhance the dataset's ability to identify anomalies.
   - Used visualizations like histograms, scatter plots, and heatmaps for data interpretation.

2. **Unsupervised Learning for Anomaly Detection**:
   - Applied algorithms like **HBOS**, **ECOD**, **PCA**, and **KNN** to detect anomalies in various datasets (e.g., healthcare and credit card transactions).
   - Justified the identification of anomalies based on average statistics and visual analysis.

3. **Supervised Learning for Anomaly Detection**:
   - Developed predictive models for mortgage probability of default using techniques like:
     - **Random Forest** (RF)
     - **Gradient Boosting Machine** (GBM)
     - **XGBoost**
     - **Generalized Linear Model** (GLM)
     - **Deep Learning**
   - Experimented with balancing techniques (e.g., `balance_classes`) and hyperparameter tuning to optimize performance.

4. **SHAP Value Analysis**:
   - Used **SHAP (SHapley Additive exPlanations)** to interpret Random Forest models for mortgage default prediction.
   - Generated summary, dependence, and force plots to explain feature importance and individual predictions.

5. **Feature Engineering and Preprocessing**:
   - Created and revised features to improve anomaly detection and model performance.
   - Preprocessed data with imputation, normalization, and dummy encoding for compatibility with machine learning algorithms.

6. **Model Evaluation**:
   - Assessed models using metrics like:
     - **ROC (Receiver Operating Characteristic) Curve**
     - **Cumulative Lift**
     - **Precision-Recall**
   - Compared models and discussed their strengths and limitations.

7. **Grid Search and Hyperparameter Tuning**:
   - Conducted extensive grid search for optimal hyperparameters (e.g., alpha, lambda, number of trees).
   - Analyzed the impact of hyperparameters on model performance and precision.

## Assignments Summary
1. **EDA and Feature Engineering**:
   - Built new features and structured EDA for datasets like healthcare billing and credit card transactions.
   - Derived actionable insights from trends and patterns.

2. **Unsupervised Learning with PyOD**:
   - Applied algorithms such as HBOS, ECOD, PCA, and KNN to detect anomalies.
   - Interpreted anomalies and justified their identification with statistical evidence.

3. **Supervised Learning with Sampling**:
   - Experimented with over- and under-sampling methods to improve model predictability for imbalanced datasets.
   - Evaluated models on key performance metrics.

4. **Advanced Models**:
   - Developed and optimized models like GBM, XGBoost, Deep Learning, and GLM for anomaly detection and classification tasks.
   - Explored AutoML for automated model selection and performance tuning.

5. **Explainability with SHAP**:
   - Used SHAP values to interpret feature importance and explain model predictions.
   - Generated visualizations to demonstrate relationships between features and the target variable.

## Tools and Technologies
- **Languages**: Python
- **Libraries**:
  - Data Analysis: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`, `shap`
  - Machine Learning: `scikit-learn`, `pyod`, `h2o`, `xgboost`
  - Sampling: `imbalanced-learn`
- **Development Environment**: Jupyter Notebook

## Key Learning Outcomes
1. Mastery of anomaly detection techniques in both supervised and unsupervised contexts.
2. Enhanced skills in feature engineering, data preprocessing, and exploratory analysis.
3. Experience in applying machine learning models to real-world datasets and interpreting results.
4. Proficiency in explaining complex models using tools like SHAP for transparency and business communication.


## Conclusion
This course has provided a deep understanding of anomaly detection and interpretability techniques, equipping me with practical skills to tackle complex datasets and derive actionable insights. The assignments emphasized hands-on learning, rigorous analysis, and effective communication of results.


