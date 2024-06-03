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
pip install numpy'''

## Data Processing and Analysis
This project utilizes PySpark for scalable data processing and analysis. The workflow involves:

Data Ingestion: Loading crime and weather datasets into PySpark DataFrames.
Data Cleaning: Handling missing values, converting data types, and filtering irrelevant records to ensure data quality.
Data Integration: Merging crime and weather datasets on common keys, such as date and location.
Feature Engineering: Creating new features that capture the interaction between weather conditions and crime rates.
Exploratory Data Analysis (EDA): Visualizing data to identify trends, patterns, and anomalies.
Machine Learning: Implementing regression and classification models to predict crime rates based on weather conditions.
