# Chicago Crime and Weather Analysis

## Overview

This project analyzes the correlation between weather conditions and crime rates in Chicago. Using Apache PySpark, we process large datasets containing detailed records of crimes and weather conditions, perform data cleaning, and integrate these datasets to explore potential patterns.

## Project Proposal
- [Project Proposal Presentation](https://tome.app/shoumik-e08/analyzing-the-impact-of-weather-conditions-on-crime-rates-in-chicago-clte1t9b903rzpm627ohilnpb) - This presentation outlines the objectives, methods, and expected outcomes of our analysis on how weather conditions impact crime rates in Chicago. It provides a detailed overview of the proposed methodologies, data sources, and analytical techniques that will be used to explore the correlation between weather patterns and criminal activities.

## Dependencies

To run this project, the following libraries need to be installed in a PySpark environment:

```bash
pip install pyspark
pip install pandas
pip install matplotlib
pip install seaborn
pip install numpy```

**Data Processing and Analysis**

PySpark enables scalable data processing and analysis. The workflow includes:

* **Data Ingestion:** Loading crime and weather data into PySpark DataFrames.
* **Data Cleaning:** Handling missing values, converting data types, and filtering irrelevant data to ensure quality.
* **Data Integration:** Merging crime and weather datasets based on shared keys like date and location.
* **Feature Engineering:** Creating new features that capture interactions between weather and crime rates.
* **Exploratory Data Analysis (EDA):** Visualizing data to identify trends, patterns, and anomalies.
* **Machine Learning:** Implementing regression and classification models to predict crime rates based on weather conditions.

**Machine Learning Models**

* **Linear Regression:** Predicts crime counts based on continuous weather features.
    * Metrics: R² Score: 0.67, Mean Absolute Error: 5.3
* **Decision Tree Classifier:** Classifies crime types based on categorical and continuous weather features.
    * Metrics: Accuracy: 72%, Precision: 0.70, Recall: 0.72
* **Random Forest Regressor:** Improves prediction accuracy by averaging multiple decision trees.
    * Metrics: R² Score: 0.74, Mean Absolute Error: 4.8
* **Gradient Boosting Regressor:** Sequentially builds models to address errors from previous models.
    * Metrics: R² Score: 0.78, Mean Absolute Error: 4.5

**Key Features**

* **Scalability:** PySpark efficiently handles large datasets.
* **Visualization:** Matplotlib and Seaborn create insightful data visualizations.
* **Modeling:** Advanced machine learning techniques uncover hidden patterns.
