# Airline Customer Churn Analysis
End to End Data Analytics and Machine Learning Project

## Project Overview
This project demonstrates an end to end analytical approach to understanding and predicting customer churn in the airline industry using real world data. The objective was not only to build a high performing predictive model, but also to identify actionable business drivers of churn that could support customer retention strategies and product decision making.

## Problem Statement
The main purpose of this dataset is to predict whether a future customer would be satisfied with their service given the details of the other parameters values. Also the airlines need to know on which aspect of the services offered by them have to be emphasized more to generate more satisfied customers.

## About Dataset
This data given by an airline organization. The dataset consists of the details of customers who have already flown with them. The feedback of the customers on various context and their flight data has been consolidated.
### Column Description:
1. Gender: Gender of the passengers (Female, Male)
2. Customer Type: The customer type (Loyal customer, disloyal customer)
3. Age: The actual age of the passengers
4. Type of Travel: Purpose of the flight of the passengers (Personal Travel, Business Travel)
5. Class: Travel class in the plane of the passengers (Business, Eco, Eco Plus)
6. Flight distance: The flight distance of this journey
7. Inflight wifi service: Satisfaction level of the inflight wifi service.
8. Departure/Arrival time convenient: Satisfaction level of Departure/Arrival time convenient
9. Ease of Online booking: Satisfaction level of online booking
10. Gate location: Satisfaction level of Gate location
11. Food and drink: Satisfaction level of Food and drink
12. Online boarding: Satisfaction level of online boarding
13. Seat comfort: Satisfaction level of Seat comfort
14. Inflight entertainment: Satisfaction level of inflight entertainment
15. On-board service: Satisfaction level of On-board service
16. Leg room service: Satisfaction level of Leg room service
17. Baggage handling: Satisfaction level of baggage handling
18. Check-in service: Satisfaction level of Check-in service
19. Inflight service: Satisfaction level of inflight service
20. Cleanliness: Satisfaction level of Cleanliness
21. Departure Delay in Minutes: Minutes delayed when departure
22. Arrival Delay in Minutes: Minutes delayed when Arrival
23. Satisfaction: Airline satisfaction level(satisfied, neutral or dissatisfied)
Labelled satisfied : 0 (Not at risk to churn), 1 neutral or dissatisfied : 1 (At risk to churn)

## Methodology (End to End Workflow)

### Data Understanding & Cleaning
1. Checked missing values, duplicates, and data consistency.
2. Applied median imputation for missing values.
3. Performed outlier detection and distribution analysis.
4. Ensured data quality before modeling.

### Exploratory Data Analysis (EDA)
1. Analyzed churn patterns across demographics and service features.
2. Visualized relationships using bar plots, pie chart, and correlation heatmaps.
3. Identified early churn signals such as service dissatisfaction and delays.

### Feature Engineering & Selection
1. Checked multicollinearity using correlation analysis and by VIF.
2. Selected features with strong predictive power and business relevance.

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
1. Service related factors (inflight wifi service, inflight entertainment, online boarding) were strong churn drivers.
2. Customers with lower satisfaction scores had significantly higher churn probability.
3. Loyalty-related features played a critical role in retention.

#### Insights can directly inform:
1. Customer experience improvements.
2. Targeted retention campaigns.
3. Product and service prioritization.

## Results & Impact
1. Built a robust churn prediction model with high accuracy and reliability
2. Delivered interpretable insights aligned with business decision-making

#### Demonstrated strong command over:
1. Data preprocessing
2. Statistical reasoning
3. Model evaluation
4. Insight communication
