# Credit Card Fraud Detection Using Unsupervised Learning

## Assignment Overview
This assignment focuses on identifying anomalous credit card transactions using **unsupervised machine learning methods**. The analysis involves refining features, applying anomaly detection algorithms (HBOS and ECOD), and interpreting the results with meaningful business insights.

## Dataset Description
- **Domain**: Credit card transactions and fraud detection.
- **Key Features**:
  - Transaction details including amounts, frequencies, and categories.
  - Derived features focusing on patterns and deviations in transaction behavior.
- **Objective**: Detect anomalies that may indicate fraudulent activities.

## Objectives
1. **Feature Engineering**:
   - Revise and improve existing features to enhance their ability to identify anomalies.
   - Create new features that capture significant transactional patterns.
2. **Apply Unsupervised Learning Methods**:
   - **HBOS (Histogram-Based Outlier Score)**:
     - Identifies anomalies using feature distributions.
     - Assumes independence among features and computes outlier scores based on histograms.
   - **ECOD (Empirical Cumulative Outlier Detection)**:
     - Leverages empirical cumulative distribution functions to detect outliers.
     - No distributional assumptions are required, making it suitable for various data types.
3. **Explain Anomalies**:
   - Interpret why specific transactions are flagged as anomalous.
   - Provide business insights into how these anomalies can aid in fraud detection.

## Key Sections
1. **Introduction**:
   - Overview of the dataset, objectives, and methods used.
2. **Method Descriptions**:
   - Detailed explanations of HBOS and ECOD in 2-3 sentences each.
   - Justifications for their use in anomaly detection.
3. **Feature Engineering**:
   - A list of revised and new features with justifications for each.
4. **Analysis**:
   - Application of HBOS and ECOD to the dataset.
   - Exploration of hyperparameter ranges for optimal results.
   - Summary statistics and visualizations of anomalies.
5. **Insights**:
   - Identification of outliers and their significance.
   - Business implications for fraud detection.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data manipulation.
  - `matplotlib` and `seaborn` for visualization.
  - `pyod` for anomaly detection algorithms.
- **Development Environment**:
  - Jupyter Notebook for structured analysis and documentation.

## Deliverables
- **HTML Report**: A comprehensive Jupyter Notebook exported as HTML, including:
  - Feature engineering process.
  - Application of HBOS and ECOD.
  - Visualizations and insights into anomalies.
- **Business Insights**:
  - Practical recommendations for utilizing anomaly detection in real-world fraud detection scenarios.
