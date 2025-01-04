# Exploratory Data Analysis (EDA) and Feature Engineering Assignment

## Assignment Overview
This assignment focuses on analyzing a **healthcare billing dataset** containing information about provider charges, payments, and discharges for different medical services. The goal is to conduct an **Exhaustive Exploratory Data Analysis (EDA)** and create meaningful features to derive insights and detect anomalies in healthcare billing practices.

## Dataset Description
- **Domain**: Healthcare billing and coverage.
- **Key Features**:
  - **Provider Information**: Includes provider ID, name, location (city, state, zip code), and hospital referral region.
  - **Service Metrics**:
    - `Total Discharges`: Number of patients discharged for specific medical services.
    - `Average Covered Charges`: Average amount billed by providers for services rendered.
    - `Average Total Payments`: Average total payments received, including insurance and patient contributions.
    - `Average Medicare Payments`: Payments covered by Medicare.
- **Size and Scope**: 163,065 records with 12 columns, offering a comprehensive view of healthcare provider billing data.

## Objectives
1. **Exploratory Data Analysis**:
   - Investigate the distribution of service metrics like discharges, charges, and payments.
   - Explore relationships between variables to uncover trends and patterns.
   - Identify potential anomalies or outliers in the data.
2. **Feature Engineering**:
   - Create 10-15 new features to enhance the dataset's informational content.
   - Examples include ratios (`charge_to_payment_ratio`), efficiency metrics (`discharge_efficiency`), and normalized scores.
   - Justify each feature's relevance to anomaly detection in healthcare billing.
3. **Insights and Anomalies**:
   - Use visualizations and statistical analysis to highlight patterns and deviations in provider billing practices.

## Key Tasks and Methodology
1. **EDA**:
   - Visualize the distribution of service metrics (`X`) and explore their relationships with other variables (`Y`).
   - Analyze interactions between variables to identify trends.
   - Tools: `seaborn`, `matplotlib`, and `pandas`.

2. **Feature Engineering**:
   - Develop diverse features such as ratios, normalized values, and categorical aggregations.
   - Each feature includes a detailed justification of its usefulness for identifying anomalies.

3. **Insights**:
   - Summarize findings from the EDA and feature engineering process.
   - Highlight business insights relevant to healthcare providers, such as inefficiencies or irregularities in billing.

## Deliverables
- **Final Submission**: An HTML report containing:
  - Comprehensive EDA with markdown explanations and visualizations.
  - Feature engineering process with justifications and insights.
  - A summary of actionable findings for anomaly detection.

## Tools and Libraries
- **Python Libraries**:
  - `pandas` for data manipulation.
  - `seaborn` and `matplotlib` for visualization.
  - `scikit-learn` for potential data scaling or transformations.
- **Environment**: Jupyter Notebook for structured analysis and reporting.

## Business Insights
- The analysis uncovered patterns and trends in healthcare billing practices, enabling:
  - **Fraud Detection**: Identifying outliers or unusual billing patterns.
  - **Operational Efficiency**: Highlighting providers with inefficient discharges or excessive charges.
  - **Data-Driven Decisions**: Informing policy changes to improve healthcare billing and coverage efficiency.
