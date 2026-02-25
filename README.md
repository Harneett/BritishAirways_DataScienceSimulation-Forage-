# BritishAirways Customer Booking Prediction

## Overview
This project analyses airline customer booking data and builds a machine learning model to predict whether a customer will complete a booking.

This project was completed as part of the British Airways Data Science Virtual Job Simulation on Forage.

A Random Forest Classifier was used along with stratified cross-validation to evaluate predictive performance and identify key drivers of booking behaviour.

## Business Problem
Airline aims to improve booking conversion rates and optimize marketing strategies. 

The objective of this project is to:
- Predict whether a customer will complete a booking
- Identify the most important factors influencing booking behaviour
- Generate insights that could support revenue optimization and customer targeting

Target Variable: 
-`booking_complete` (1 = booking completed, 0 = not completed)

## Dataset
- Approx. 50,000 airline customer booking records
- Mix of numerical and categorical features
- Includes behavioural and booking-related variables

---

Note:
The original dataset provided in the simulation is not included in this repository in accordance with platform terms. All analysis and code are my own work.

---

## Methodology
1. Exploratory Data Analysis (EDA)
2. Data preprocessing and feature engineering
   - Handling missing values
   - One-hot encoding categorical variables
   - Stratified train-test split
3. Model Development
   - Random Forest Classifier
4. Model Evaluation
   - 5-fold stratified cross-validation
   - Accuracy
   - Classification metrics
5. Feature Importance Analysis

---

## Results
The Random Forest model demonstrated strong predictive performance in identifying booking completion patterns.

Key insights include:
- Certain booking channels significantly influence completion rates
- Trip-related variables play a strong role in predicting customer behaviour
- Feature importance analysis reveals actionable drivers of conversion

---

## Repository Structure

'''
british-airways-booking-prediction/
|
├── customer_buying_behaviour.ipynb
├── Customer_booking_prediction.pptx
├── requirements.txt
└── README.md
'''

---

## Key Skills Demonstrated

- Data cleaning and preprocessing
- Exploratory data analysis
- Machine learning model development
- Cross-validation
- Model evaluation and interpretation
- Business insight communication

---

## Tools & Technologies

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
- Jupyter Notebook

---

## Disclaimer

This project is based on a virtual job simulation provided by Forage. The dataset and task materials are not redistributed. This repository contains only my original analysis and implementation.

---

## Author

Harneet Kaur
Aspiring Data Analyst | Data Science Enthusiast
