# Flight Price Prediction and RFM Analysis

## Project Overview

This repository contains a comprehensive project that aims to predict flight ticket prices using various machine learning algorithms and to conduct a Recency, Frequency, and Monetary (RFM) analysis on customer data. The project involves data cleaning, feature engineering, exploratory data analysis (EDA), model training, and evaluation.

## Flight Price Prediction

### Dataset
The flight price prediction is based on a dataset (`Flight_Price_Train.xlsx`) containing various attributes related to flights, such as:
* Airline
* Source
* Destination
* Departure Time
* Arrival Time
* Duration
* Additional Info

### Key Steps
1. **Data Preprocessing**: 
   * Removed duplicates and null values.
   * Converted date columns to datetime format.
   * Extracted day, month, and year from the journey date.
   * Encoded categorical features.

2. **Exploratory Data Analysis (EDA)**: 
   * Visualized flight price distributions.
   * Analyzed the correlation between different features.
   * Identified outliers and potential anomalies.

3. **Model Building**: 
   * Split the dataset into training and testing sets.
   * Trained various regression models including:
     * Linear Regression
     * Random Forest Regressor
     * Gradient Boosting Regressor
   * Tuned hyperparameters for optimal performance.

4. **Model Evaluation**: 
   * Assessed model performance using metrics such as:
     * Mean Absolute Error (MAE)
     * Mean Squared Error (MSE)
     * R-squared

## RFM Analysis

### Purpose
RFM analysis is used to identify valuable customers based on their transaction history by analyzing three key metrics:
* **Recency**: How recently a customer made a purchase.
* **Frequency**: How often a customer makes a purchase.
* **Monetary**: How much money a customer spends.

### Key Steps
1. **Data Preparation**: 
   * Aggregated transaction data to calculate RFM scores.
   * Defined thresholds for classifying customers into different segments.

2. **Segmentation**: 
   * Created customer segments such as:
     * High-Value Customers
     * At-Risk Customers
     * New Customers

3. **Visualization**: 
   * Visualized RFM scores to identify patterns and trends.
   * Developed targeted marketing strategies based on customer segments.

