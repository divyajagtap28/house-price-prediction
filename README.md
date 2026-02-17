House Price Prediction using Simple Linear Regression
Project Overview

This project builds a Simple Linear Regression model to predict residential house prices based on property area (in square feet).

The objective is to analyze how property size impacts market price and develop a predictive model that estimates property valuation accurately.

Problem Statement

In the real estate industry, property size is one of the most influential factors affecting price.

This project aims to:

Understand the relationship between area and price

Quantify price increase per additional square foot

Build a regression model to estimate house prices

Evaluate model performance using statistical metrics

Derive business insights from the results

Input Variable

Area (sq.ft)

Output Variable

Price (₹)

Dataset Description

The dataset contains 100 residential property records with realistic variation.

Column	Description
Area	Property size in square feet
Price	Property price in Indian Rupees

The data simulates real market behavior with natural fluctuations.

Technologies Used

Python

Pandas

NumPy

Matplotlib

Scikit-learn

Jupyter Notebook

Project Workflow

Data Loading and Exploration

Data Visualization (Scatter Plot)

Correlation Analysis

Train-Test Split

Model Training using Linear Regression

Model Evaluation (R², MSE, RMSE)

Regression Line Visualization

Business Insights and Interpretation

Model Equation

Price = m × Area + c

Where:

m = Price increase per square foot (model coefficient)

c = Base price (intercept)

Model Performance

Strong positive correlation between area and price

High R² score (approximately 95%+)

Low prediction error (RMSE)

The model demonstrates that area is a significant factor in determining property value.

Business Insights

House prices increase approximately ₹4,800–₹5,000 per additional square foot.

There is a strong positive relationship between property size and price.

The model explains a large percentage of price variation.

Buyers can estimate fair property prices before purchasing.

Sellers can use the model for competitive pricing strategies.

Limitations

This model considers only area as a feature. Real estate pricing also depends on:

Location

Number of bedrooms

Amenities

Property age

Future models can incorporate these features for improved accuracy.

Project Structure
house-price-prediction/
│
├── house_prices.csv
├── house_price_prediction.ipynb
├── README.md
└── requirements.txt

Future Improvements

Multiple Linear Regression (Area + Bedrooms + Location)

Feature Engineering

Model Deployment using Streamlit

Model comparison with Polynomial Regression

How to Run the Project

Clone the repository:

git clone https://github.com/yourusername/house-price-prediction.git


Install dependencies:

pip install -r requirements.txt


Open Jupyter Notebook:

jupyter notebook


Run house_price_prediction.ipynb

Author

Divya Jagtap
Machine Learning Project