# SpaceX Falcon 9 Launch Prediction Capstone Project

## Introduction

This project is part of the IBM Data Science Professional Certificate Capstone and aims to predict whether the first stage of SpaceX's Falcon 9 rocket will land successfully. SpaceX has revolutionized the space industry by significantly lowering launch costs through the reusability of the first stage of their rockets. Predicting the success of a Falcon 9 landing can provide critical insights for cost optimization and potential competitors, offering a competitive edge in the rocket launch industry.

## Problem Statement

The goal of this project is to predict whether the Falcon 9 first-stage rocket will land successfully after launch. SpaceX has reduced launch costs significantly by reusing the first stage, and accurately predicting its landing success could help SpaceX optimize launch costs. This prediction could also offer valuable insights to companies considering bidding against SpaceX.

## Approach and Workflow

### 1. Data Collection and Cleaning

The dataset for this project was collected through API calls and web scraping techniques. The data includes various features such as launch success, vehicle configuration, and the launch site. After data collection, several data cleaning steps were performed to handle missing values, normalize categorical variables, and ensure the dataset was ready for analysis.

### 2. Exploratory Data Analysis (EDA)

Exploratory Data Analysis (EDA) was conducted to understand the underlying patterns and relationships in the data. Visualizations such as scatter plots, bar charts, and correlation matrices were created to explore key factors influencing landing success, including the launch vehicle configuration, launch site, and flight number. These insights guided the selection of relevant features for the machine learning models.

### 3. Interactive Visual Analytics and Dashboards

An interactive dashboard was developed using Plotly Dash to analyze the launch records visually. This dashboard includes pie charts and scatter plots that provide an interactive way to explore the data. Additionally, an interactive map was created using the Folium library to analyze the proximity of launch sites and their correlation with landing success. This helped visualize spatial relationships and launch patterns.

### 4. Predictive Modeling

Machine learning models, including Support Vector Machines (SVM), Decision Trees, and Logistic Regression, were applied to predict the landing success. The data was split into training and testing datasets, and hyperparameter tuning was performed using grid search to optimize the models. Performance metrics such as accuracy, precision, recall, and F1-score were used to evaluate and compare model performance.

### 5. Model Evaluation and Final Results

After testing multiple classification models, the Random Forest Classifier was selected as the best performing model. It achieved an accuracy of 85% in predicting the landing success, with a precision of 87% and recall of 83%. The model's performance indicates that it can effectively predict whether the first stage of Falcon 9 will land successfully, which is crucial for SpaceX's cost optimization strategies.

## Key Learnings and Insights

- **Data Wrangling**: Cleaning and preprocessing the raw data was critical to ensure accuracy and completeness. Proper handling of missing values, feature scaling, and encoding categorical variables contributed to better model performance.
- **Feature Engineering**: Feature selection and engineering played a vital role in determining which attributes most influenced the success of Falcon 9 landings.
- **Model Performance**: By testing multiple algorithms, the Random Forest Classifier emerged as the top model, balancing accuracy and interpretability, making it ideal for this type of prediction.

## Conclusion

This capstone project demonstrates how data science techniques, including data wrangling, exploratory analysis, feature engineering, and machine learning, can be applied to solve a real-world problem. Predicting the success of Falcon 9 first-stage landings not only aids SpaceX in optimizing costs but also provides valuable insights that can be used by other companies considering bids for rocket launches. The interactive dashboards and maps built during the project further enhance the ability to analyze and visualize key factors influencing launch outcomes.

