# Machine-Learning-Enabled-Business-Intelligence-for-Dynamic-Pricing-Strategies



ML-Enabled-Business-Intelligence-for-Airbnb-Dynamic-Pricing/
│
├── data/
│   ├── raw_dataset.csv
│   └── cleaned_dataset.csv
│
├── notebooks/
│   ├── data_cleaning.ipynb
│   ├── eda.ipynb
│   └── model_training.ipynb
│
├── models/
│   └── trained_model.pkl
│
├── dashboard/
│   └── Airbnb_Dynamic_Pricing.pbix
│
├── images/
│   └── dashboard_screenshots
│
├── README.md
│
└── requirements.txt
 ## Project Overview

This project combines Machine Learning and Business Intelligence to analyze Airbnb listings and generate dynamic pricing recommendations. The system predicts optimal listing prices based on demand patterns, availability, reviews, room types, and location characteristics.

The final solution integrates data analytics, machine learning models, and interactive Power BI dashboards to support pricing optimization and business decision-making.


## Objectives

- Analyze Airbnb listing data from NYC.
- Identify demand and pricing patterns.
- Build machine learning models to predict listing prices.
- Generate dynamic pricing recommendations.
- Develop interactive Power BI dashboards for business users.
- Support revenue optimization and decision making.



## Dataset

Source: Kaggle

Dataset: NYC Airbnb Listings Dataset

Records: 48,410 listings

Features include:

- Neighbourhood
- Room Type
- Price
- Reviews
- Availability
- Latitude
- Longitude
- Demand Index



## Project Workflow

1. Data Collection
2. Data Cleaning
3. Feature Engineering
4. Exploratory Data Analysis
5. Machine Learning Model Development
6. Model Evaluation
7. Dynamic Pricing Generation
8. Power BI Dashboard Development
9. Business Insights and Recommendations


## Machine Learning Models

The following regression models were evaluated:

- Linear Regression
- Random Forest Regressor
- XGBoost Regressor

Evaluation Metrics:

- RMSE (Lower is Better)
- MAE (Lower is Better)
- R² Score (Higher is Better)

The best-performing model was selected to generate the final predicted prices.





## Dynamic Pricing Logic

The machine learning model predicts market-aligned prices based on listing characteristics.

Dynamic pricing recommendations are generated using:

- Predicted Price
- Demand Index
- Reviews
- Availability
- Location Factors

The system identifies pricing opportunities and potential revenue improvements.

## Power BI Dashboard

The dashboard consists of four pages:

### Page 1: Executive Overview
- Total Listings
- Average Price
- Average Predicted Price
- Average Dynamic Price
- Borough Analysis

### Page 2: Demand Analysis
- Demand Index
- Reviews Analysis
- Availability Analysis
- Demand by Borough
- Demand by Room Type

### Page 3: Dynamic Pricing Recommendations
- Current vs Dynamic Price
- Price Uplift Analysis
- Revenue Optimization Insights

### Page 4: Geographic Market Insights
- Location-Based Analysis
- Borough Pricing Patterns
- Demand Hotspots




## Technology Stack

- Python
- Pandas
- NumPy
- Scikit-Learn
- XGBoost
- Jupyter Notebook
- Power BI
- Kaggle Dataset

## Business Value

This solution helps:

- Airbnb Hosts
- Property Managers
- Revenue Managers
- Business Analysts

Benefits:

- Dynamic Pricing Recommendations
- Revenue Optimization
- Demand Forecasting
- Location-Based Market Insights


## Future Enhancements

- Real-Time Dynamic Pricing
- Booking Demand Forecasting
- Seasonal Trend Analysis
- API Integration
- Automated Dashboard Refresh


## Author

 Sri Surya Satya Sai Chavakula

Master's Project

Machine Learning Enabled Business Intelligence for Dynamic Pricing





