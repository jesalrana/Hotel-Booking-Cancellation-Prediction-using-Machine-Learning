# Hotel Booking Cancellation Prediction using Machine Learning

## Project Overview

This machine learning project focuses on predicting hotel booking cancellations using customer behavior, booking patterns, and pricing data.

The objective is to help hotel businesses reduce revenue leakage, improve occupancy forecasting, and optimize cancellation policies using predictive analytics.

The dataset contains 36,275 hotel booking records from INN Hotels Group.

## Business Problem

Hotel cancellations directly impact revenue planning, room inventory, staffing, and customer experience.

This project aims to identify the key factors behind booking cancellations and build predictive models that help hotel management proactively reduce cancellations.

## Dataset Information

The dataset includes:

- Customer demographics
- Number of adults and children
- Lead time
- Room type
- Meal plan
- Market segment
- Average room price
- Repeat guest status
- Previous cancellations
- Special requests
- Booking status (Target Variable)

## Exploratory Data Analysis (EDA)

Key insights:

- Around 32.8% of bookings were canceled.
- Longer lead times show higher cancellation probability.
- Higher room prices increase cancellation risk.
- Repeat guests cancel significantly less.
- Guests with special requests are less likely to cancel.
- Online bookings show higher cancellation rates.

## Data Preprocessing

Performed:

- Missing value analysis
- Outlier detection using IQR
- Outlier capping
- Categorical encoding
- Feature engineering
- Train-test split

## Machine Learning Models

### 1. Logistic Regression
Performance:

- Accuracy: ~82.5%
- ROC-AUC: ~0.91

### 2. Random Forest / Tree-Based Model
Performance:

- Accuracy: ~88%
- ROC-AUC: ~0.97

## Model Comparison

Tree-based models outperformed logistic regression due to better handling of nonlinear relationships and feature interactions.

## Key Business Insights

Important predictors:

- Lead Time
- Average Price per Room
- Market Segment
- Previous Cancellations
- Repeat Guest Status
- Special Requests

## Business Recommendations

- Apply dynamic cancellation policies for high-risk bookings.
- Introduce deposit-based booking confirmation.
- Encourage personalization during booking.
- Reward repeat guests through loyalty programs.
- Reduce OTA dependency by promoting direct bookings.

## Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels

## Author

Jesal Ajit Rana
