# Healthcare Dataset Anomaly Detection Using Autoencoder and iForest

## Assignment Overview
This assignment utilizes **unsupervised learning techniques** to detect anomalies in a **healthcare dataset**. The focus is on applying **Autoencoder** and **Isolation Forest (iForest)** algorithms to identify providers with unusual patterns in their service metrics. A thorough explanation of each algorithm, their application, and the results is included.

## Dataset Description
- **Domain**: Healthcare billing and operational metrics.
- **Key Features**:
  - **Provider Information**: Provider ID, location, and referral region.
  - **Service Metrics**:
    - `Total Discharges`: Number of patient discharges per medical service.
    - `Average Covered Charges`: Costs billed by providers.
    - `Average Payments`: Payments made, including Medicare contributions.
- **Objective**: Identify anomalous providers that warrant further inspection due to unusual patterns in billing or operational behavior.

## Objectives
1. **Algorithm Descriptions**:
   - **Autoencoder**:
     - A neural network-based unsupervised learning method.
     - Learns a compressed representation of data and reconstructs the input; reconstruction errors highlight anomalies.
   - **Isolation Forest (iForest)**:
     - A tree-based ensemble method that isolates anomalies by randomly splitting the data.
     - Data points requiring fewer splits to isolate are considered anomalies.
2. **Analysis**:
   - Apply Autoencoder and iForest to identify anomalous providers.
   - Calculate the proportion and count of anomalies detected.
   - Analyze and justify anomalies based on average statistics and variable deviations.
3. **Insights**:
   - Provide business-relevant justifications for identified anomalies.

## Key Sections
1. **Introduction**:
   - Overview of dataset and unsupervised learning methods.
2. **Method Descriptions**:
   - Clear explanations of Autoencoder and iForest.
3. **Feature Standardization**:
   - All variables are standardized to ensure consistency across metrics.
4. **Analysis**:
   - Application of Autoencoder and iForest, including parameter tuning.
   - Visualization of results and clustering of anomalies.
5. **Insights**:
   - Summary of anomalous providers and their business implications.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` and `numpy` for data preprocessing.
  - `matplotlib` and `seaborn` for visualization.
  - `pyod` for implementing Autoencoder and iForest.
- **Development Environment**:
  - Jupyter Notebook for structuring the analysis and documentation.

## Deliverables
- **HTML Report**: A comprehensive notebook exported as an HTML file, including:
  - Explanations of methods.
  - Anomaly detection analysis with Autoencoder and iForest.
  - Visualizations and summary statistics.
- **Business Insights**:
  - Recommendations for further investigation based on identified anomalies.
