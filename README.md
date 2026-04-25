# Walmart Sales Forecasting

## Overview
This project focuses on analyzing and forecasting Walmart weekly sales using data analysis and machine learning techniques. The objective is to understand sales patterns, identify key influencing factors, and build predictive models for accurate forecasting.

---

## Objectives
- Analyze historical sales data to identify trends and seasonality  
- Perform feature engineering to capture time-based patterns  
- Build and evaluate machine learning models for sales prediction  
- Derive insights to support business decision-making  

---

## Dataset

The project uses the Walmart Store Sales dataset, which consists of multiple files:

- **train.csv** – Historical weekly sales data (target variable: Weekly_Sales)  
- **test.csv** – Test dataset for prediction  
- **features.csv** – External features such as temperature, fuel price, CPI, unemployment, and holiday indicators  
- **stores.csv** – Store-level metadata including store type and size  

### Key Features Used
- Store  
- Department (Dept)  
- Weekly_Sales  
- IsHoliday  
- Temperature, Fuel Price, CPI, Unemployment  
- Store Type and Size  

### Data Preparation
- Merged train, features, and store datasets using Store and Date  
- Converted Date column to datetime format  
- Extracted time-based features such as Week and Year  
- Cleaned and structured data for modeling  

---

## Approach

### 1. Exploratory Data Analysis
- Analyzed sales trends across different years  
- Compared performance across stores and departments  
- Identified seasonal patterns and holiday-driven demand spikes  
- Used visualizations such as line plots, bar charts, and heatmaps  

### 2. Feature Engineering
- Created time-based features (Week, Year)  
- Selected relevant variables for model training  

### 3. Model Building
- Implemented Ridge Regression with hyperparameter tuning using GridSearchCV  
- Built Random Forest Regressor for improved performance  

### 4. Model Evaluation
- Evaluated models using:
  - Root Mean Squared Error (RMSE)  
  - R-squared (R2)  

- Random Forest achieved strong performance with:
  - R2 ~ 0.97 on test data  

---

## Results
- Identified clear seasonal sales patterns across weeks and years  
- Observed variation in performance across stores and departments  
- Random Forest model provided high accuracy for sales forecasting  

---

## Technologies Used
- Python  
- Pandas, NumPy  
- Matplotlib, Seaborn  
- Scikit-learn  

---

## Project Structure
