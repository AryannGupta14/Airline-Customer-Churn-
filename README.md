# Airline Customer Churn Analysis
End to End Data Analytics and Machine Learning Project

## Project Overview
This project demonstrates an end to end analytical approach to understanding and predicting customer churn in the airline industry using real world data. The objective was not only to build a high performing predictive model, but also to identify actionable business drivers of churn that could support customer retention strategies and product decision making.

## Problem Statement
The main purpose of this dataset is to predict whether a future customer would be satisfied with their service given the details of the other parameters values. Also the airlines need to know on which aspect of the services offered by them have to be emphasized more to generate more satisfied customers.

## About Dataset
This data given by an airline organization. The dataset consists of the details of customers who have already flown with them. The feedback of the customers on various context and their flight data has been consolidated.
### Column Description:
Gender: Gender of the passengers (Female, Male)
Customer Type: The customer type (Loyal customer, disloyal customer)
Age: The actual age of the passengers
Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)
Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)
Flight distance: The flight distance of this journey
Inflight wifi service: Satisfaction level of the inflight wifi service.
Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
Ease of Online booking: Satisfaction level of online booking
Gate location: Satisfaction level of Gate location
Food and drink: Satisfaction level of Food and drink
Online boarding: Satisfaction level of online boarding
Seat comfort: Satisfaction level of Seat comfort
Inflight entertainment: Satisfaction level of inflight entertainment
On-board service: Satisfaction level of On-board service
Leg room service: Satisfaction level of Leg room service
Baggage handling: Satisfaction level of baggage handling
Check-in service: Satisfaction level of Check-in service
Inflight service: Satisfaction level of inflight service
Cleanliness: Satisfaction level of Cleanliness
Departure Delay in Minutes: Minutes delayed when departure
Arrival Delay in Minutes: Minutes delayed when Arrival
Satisfaction: Airline satisfaction level(satisfied, neutral or dissatisfied)
Labelled satisfied : 0 (Not at risk to churn), 1 neutral or dissatisfied : 1 (At risk to churn)

## Methodology (End to End Workflow)

### Data Understanding & Cleaning
Checked missing values, duplicates, and data consistency.
Applied median imputation for missing values.
Performed outlier detection and distribution analysis.
Ensured data quality before modeling.

### Exploratory Data Analysis (EDA)
Analyzed churn patterns across demographics and service features.
Visualized relationships using bar plots, pie chart, and correlation heatmaps.
Identified early churn signals such as service dissatisfaction and delays.

### Feature Engineering & Selection
Checked multicollinearity using correlation analysis and by VIF.
Selected features with strong predictive power and business relevance.

### Model Building
Trained and compared multiple classification models:
1. Logistic Regression (baseline model)
2. Random Forest
3. XGBoost (best-performing model)

### Model Evaluation
Evaluated models using:
1. Confusion Matrix
2. Precision, Recall, F1-score
3. ROC-AUC Curve

#### XGBoost achieved an F1 score of 0.96 & ROC AUC score of 0.99, indicating excellent predictive performance

## Key Insights (Business Value)
Service related factors (inflight wifi service, inflight entertainment, online boarding) were strong churn drivers.
Customers with lower satisfaction scores had significantly higher churn probability.
Loyalty-related features played a critical role in retention.

#### Insights can directly inform:
Customer experience improvements.
Targeted retention campaigns.
Product and service prioritization.

## Results & Impact
Built a robust churn prediction model with high accuracy and reliability
Delivered interpretable insights aligned with business decision-making

#### Demonstrated strong command over:
Data preprocessing
Statistical reasoning
Model evaluation
Insight communication
