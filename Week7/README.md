# Healthcare Dataset Anomaly Detection Using Unsupervised Learning

## Assignment Overview
This project focuses on detecting anomalies in a **healthcare dataset** using **unsupervised learning techniques**. The analysis applies PCA (Principal Component Analysis) and KNN (k-Nearest Neighbors) methods from the PyOD library to identify a small cluster of suspicious providers, with detailed insights into why these providers may require further inspection.

## Dataset Description
- **Domain**: Healthcare billing and operational metrics.
- **Key Features**:
  - **Provider Information**: Details such as provider ID, location, and referral region.
  - **Service Metrics**:
    - `Total Discharges`: Number of patient discharges per medical service.
    - `Average Covered Charges`: Costs billed by providers.
    - `Average Payments`: Payments made, including Medicare contributions.
- **Objective**: Identify unusual patterns in provider charges or service delivery that may signal inefficiencies or fraud.

## Objectives
1. **Feature Engineering**:
   - Revise and standardize existing features.
   - Create new features to enhance anomaly detection.
2. **Apply Unsupervised Learning Methods**:
   - **PCA (Principal Component Analysis)**:
     - Reduces dimensionality while preserving variance.
     - Highlights deviations by projecting data into lower-dimensional space.
   - **KNN (k-Nearest Neighbors)**:
     - Identifies anomalies based on local density variations.
     - Outliers are those with sparse neighbors compared to dense regions.
3. **Explain Anomalies**:
   - Interpret why specific clusters of providers are flagged as suspicious.
   - Use average statistics of variables within clusters to justify findings.

## Key Sections
1. **Introduction**:
   - Overview of the dataset and unsupervised learning methods used.
2. **Method Descriptions**:
   - Explanation of PCA and KNN in 2-3 sentences each.
   - Justifications for their application to healthcare anomaly detection.
3. **Feature Engineering**:
   - Standardize variables to ensure consistency across metrics.
   - Introduce revised features and explain their role in anomaly detection.
4. **Analysis**:
   - Application of PCA and KNN methods, including hyperparameter tuning.
   - Visualizations of clusters and identified anomalies.
5. **Insights**:
   - Summarize findings from identified clusters.
   - Highlight business implications, such as providers requiring closer review due to higher charges or unusual patterns.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data preprocessing and manipulation.
  - `matplotlib` and `seaborn` for visualization.
  - `pyod` for implementing PCA and KNN anomaly detection methods.
- **Development Environment**:
  - Jupyter Notebook for structuring the analysis and documentation.

## Deliverables
- **HTML Report**: A comprehensive notebook exported as an HTML file, including:
  - Method explanations.
  - Anomaly detection analysis with PCA and KNN.
  - Visualizations and business insights.
- **Business Insights**:
  - Identification of anomalous clusters based on statistical differences.
  - Recommendations for further provider-level investigation.
