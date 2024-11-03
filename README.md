# Chicago Crime and Weather Analysis

## Overview

This project, completed as part of the MS in Applied Data Science program at Syracuse University's School of Information Studies, explores the correlation between weather conditions and crime rates in Chicago. By leveraging Apache PySpark, the project processes large datasets of crime incidents and weather records, performing data cleaning, integration, and machine learning to identify patterns that link weather variables to crime trends. This analysis aligns with the program’s learning outcomes, such as data collection, processing, and the application of predictive models to derive actionable insights.

## Project Proposal

- [Project Proposal Presentation](https://tome.app/shoumik-e08/analyzing-the-impact-of-weather-conditions-on-crime-rates-in-chicago-clte1t9b903rzpm627ohilnpb): This presentation outlines the objectives, methodologies, and anticipated outcomes of analyzing how weather affects crime rates in Chicago. It details the proposed data sources, integration techniques, and analytical approaches, aiming to illuminate the impact of environmental factors on crime patterns, particularly in areas of public safety and policy.

## Dependencies

To execute this project, the following libraries should be installed in a PySpark environment:

```bash
pip install pyspark pandas matplotlib seaborn numpy
```

## Data Processing and Analysis

Using PySpark enables scalable data processing and analysis on large crime and weather datasets, supporting efficient workflows to meet program learning outcomes related to data collection, processing, and access.

- **Data Ingestion:** Crime and weather datasets are loaded into PySpark DataFrames, demonstrating proficiency in data access (Outcome 1).
- **Data Cleaning:** Missing values are handled, data types are standardized, and irrelevant data is filtered out, ensuring high data quality for analysis.
- **Data Integration:** Crime and weather datasets are merged based on common keys (e.g., date and location), creating a comprehensive dataset for feature analysis (Outcome 2).
- **Feature Engineering:** New features are created to capture potential interactions between weather and crime, facilitating deeper analysis.
- **Exploratory Data Analysis (EDA):** Visualizations with Matplotlib and Seaborn reveal trends and anomalies, enhancing data interpretation and communication (Outcomes 3 and 5).
- **Machine Learning:** Various regression and classification models are implemented to predict crime rates, addressing the core outcome of applying predictive models to generate insights (Outcome 3).

## Machine Learning Models

This project employs machine learning models that align with the program’s learning outcomes, particularly in terms of predictive analysis (Outcome 3).

- **Linear Regression:** Predicts daily crime counts based on weather conditions.
    - **Metrics:** R² Score: 0.67, Mean Absolute Error: 5.3
- **Decision Tree Classifier:** Classifies types of crimes based on both categorical and continuous weather features.
    - **Metrics:** Accuracy: 72%, Precision: 0.70, Recall: 0.72
- **Random Forest Regressor:** Enhances predictive accuracy by averaging across multiple decision trees.
    - **Metrics:** R² Score: 0.74, Mean Absolute Error: 4.8
- **Gradient Boosting Regressor:** Sequentially minimizes errors from previous models to boost prediction accuracy.
    - **Metrics:** R² Score: 0.78, Mean Absolute Error: 4.5

## Key Features

- **Scalability:** PySpark enables handling of large datasets, meeting program outcomes related to data access and processing efficiency (Outcome 1).
- **Visualization:** Using Matplotlib and Seaborn, the project visualizes critical insights for easy interpretation by stakeholders (Outcome 5).
- **Advanced Modeling:** The implementation of machine learning techniques reveals patterns and predictions that support data-driven decisions in public safety.

## Results

The project delivers a comprehensive analysis of how weather conditions impact crime rates in Chicago, aiming to provide valuable insights to policymakers and law enforcement agencies. Through various visualizations and predictive models, the project identifies correlations that can inform proactive crime management strategies.

## Conclusion

This project illustrates the integration of weather data and crime statistics to uncover significant trends, demonstrating a practical application of data science principles. By employing PySpark, the analysis achieves scalability and robustness, aligning with the program’s learning objectives. This project allowed me to achieve key learning outcomes:

**1. Collect, store, and access data by identifying and leveraging applicable technologies:**  
This project involved collecting and integrating multiple datasets, including crime and weather data, and organizing them for analysis. I utilized data preprocessing techniques to ensure the data was clean and accessible.

**2. Create actionable insight across a range of contexts (e.g., societal, business, political) using data and the full data science life cycle:**  
By following the full data science life cycle—from data collection to model deployment—we generated insights that help predict crime rates and identify hotspots, offering valuable support for public safety strategies.

**3. Apply visualization and predictive models to help generate actionable insight:**  
Visualizations, such as temperature-crime correlation plots, and predictive models like the Random Forest Regressor and Classifier enabled us to uncover trends and make data-driven predictions that inform law enforcement decisions.

**4. Use programming languages such as R and Python to support the generation of actionable insight:**  
I used Python and its libraries, including Pandas, Scikit-Learn, and Matplotlib, to analyze data, build predictive models, and create visualizations, supporting the project’s analytical needs.

**5. Communicate insights gained via visualization and analytics to a broad range of audiences:**  
I contributed to creating visualizations and reports to effectively communicate our findings on weather-crime correlations and crime hotspots, making the insights accessible to both technical and non-technical stakeholders.

**6. Apply ethics in the development, use, and evaluation of data and predictive models:**  
I ensured ethical handling of sensitive crime data by maintaining data privacy and transparency, and by using model interpretability techniques to explain our predictive results responsibly.

