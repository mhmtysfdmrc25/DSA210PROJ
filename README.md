# Analysis of Daily Water Consumption, Rainfall Amount, and Dams Levels in Istanbul

## Project Overview

This project investigates the relationship between daily water consumption, rainfall levels across 10 dams, and dams' fill percentages in Istanbul over the period from 2011 to 2024. By analyzing historical data sourced from IBB Open Data Portal, this study aims to identify correlations and trends that influence water resource management.

Water consumption and reservoir levels are crucial indicators of urban sustainability, particularly in a metropolis like Istanbul, where millions depend on a stable water supply. Rainfall is a key replenishment factor, while consumption directly affects the depletion rate of water reserves. Understanding these interconnections can help forecast future reservoir levels and assist in strategic water management decisions.

The key research questions addressed in this project include:
- How strongly is water consumption correlated with rainfall amount and reservoir fill percentages?
- Are there seasonal patterns or anomalies in water consumption trends?
- Can machine learning models predict future reservoir levels based on historical data?

Using data science techniques, this project will analyze and visualize temporal patterns in water usage, precipitation, and reservoir storage. Additionally, machine learning algorithms will be employed to develop predictive models for future reservoir capacity based on historical consumption and weather trends.

# Motivation

Water shortage is a growing concern for cities worldwide, and Istanbul is no exception. By understanding the interplay between rainfall, consumption, and reservoir storage, authorities can better anticipate periods of water shortage and optimize resource allocation.

This project aims to provide actionable insights into:

- Identifying key drivers of water depletion and replenishment
- Informing policy decisions on water conservation
- Improving prediction models for future water supply sustainability

By leveraging open data from the IBB Open Data Portal, this analysis contributes to a data-driven approach to urban water management.

# Data Sources

**Daily Water Consumption Data:**  

- Collected from the IBB Open Data Portal.
- Provides daily total water consumption in cubic meters (m³/day) for Istanbul.
  
**Daily Rainfall Amount Data for each 10 Dams in Istanbul:**

- Obtained from the IBB Open Data Portal.
- Records daily precipitation (kg/m³) for each of the 10 major dams supplying water to Istanbul.

**Daily Reservoir Fill Percentage Data:**

- Extracted from the IBB Open Data Portal.
- Contains the daily percentage of storage capacity occupied in each reservoir.

# Objectives

- Conduct a correlation analysis to determine how rainfall and water consumption influence reservoir levels.
- Identify seasonal trends and anomalies in water consumption and storage levels.
- Develop a predictive machine learning model to forecast future reservoir levels based on past consumption and precipitation trends.
- Visualize the findings through interactive charts and dashboards to communicate insights effectively.
- Provide actionable recommendations for optimizing water resource management.
  
## Tools and Techniques

  **Programming:** Python (Google Colab)

  **Libraries:**

    - `pandas` for data processing
    - `matplotlib.pyplot` and `seaborn` for visualization
    - `scipy.stats` for correlation analysis
    - `scikit-learn` for machine learning models
    - `seaborn` for data visualization
    - `google.colab` for data gathering from google drive
    
  **Machine Learning Approaches:**

    - Linear Regression for correlation analysis
    - Random Forest and XGBoost for predictive modeling
    - ARIMA and LSTM for time series forecasting

  **Data Integration:**

    - Merging multiple datasets based on timestamp fields
    - Handling missing values and outliers

  **Version Control:**  GitHub for project documentation and code sharing

# Expected Outcomes

This project aims to deliver:

- A comprehensive analysis of how rainfall, water consumption, and reservoir levels are interconnected.
- Identification of seasonal variations in water consumption patterns.
- A predictive model capable of estimating future reservoir levels based on historical trends.
- Visual dashboards illustrating key findings to aid in decision-making for water management.
- Insights that could contribute to improving water sustainability policies in Istanbul.

# Limitations and Future Work

- The accuracy of predictions depends on the quality and completeness of historical data.
- External factors such as population growth, infrastructure changes, and climate variability are not explicitly accounted for in the model.
- Future research could incorporate climate change projections and urban expansion trends to refine predictive accuracy.
- Developing an early warning system for potential water shortages could be an extension of this project.

By leveraging open data and machine learning, this project contributes to a data-driven approach to water resource management, ensuring sustainable usage and long-term planning for Istanbul’s water supply.

