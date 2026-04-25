# Walmart Sales Forecasting

## Overview
This project analyzes Walmart weekly sales data and builds machine learning models to forecast sales. The goal is to identify sales patterns, understand the effect of stores/departments/holidays, and predict weekly sales using regression models.

---

## Dataset
The project uses multiple Walmart sales data files:

- `train.csv` – historical weekly sales data
- `test.csv` – test data for prediction
- `features.csv` – external factors such as temperature, fuel price, CPI, unemployment, and holiday information
- `stores.csv` – store metadata such as store type and size

The datasets were merged and processed to create a unified dataset for analysis and modeling.

---

## Key Steps
- Data cleaning and preprocessing
- Feature engineering using date-based features such as Week and Year
- Exploratory Data Analysis on sales trends, stores, and departments
- Correlation analysis between numerical features
- Model building using Ridge Regression and Random Forest Regressor
- Hyperparameter tuning using GridSearchCV
- Model evaluation using RMSE and R2 score

---

## Visualizations


### Year-wise Sales Trend
![Year-wise Sales Trend](Walmart%20Sales%20Forecasting/images/Years_Wise.png)

### Store-wise Sales
![Store-wise Sales](Walmart%20Sales%20Forecasting/images/Store_Wise.png)

### Department-wise Sales
![Department-wise Sales](Walmart%20Sales%20Forecasting/images/Dept_Wise.png)

### Correlation Heatmap
![Correlation Heatmap](Walmart%20Sales%20Forecasting/images/Correlation.png)

---

## Model Performance
The Random Forest Regressor performed better than the linear model and achieved strong predictive performance.

- Test R2 Score: approximately 0.97
- Evaluation Metrics Used: RMSE and R2 Score

---

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Conclusion
This project demonstrates how data analysis and machine learning techniques can be applied to understand sales behavior and build predictive models. The insights generated can help in better inventory planning and decision-making.

---

## Future Improvements
- Apply advanced models such as XGBoost or time-series forecasting techniques  
- Incorporate additional external factors for better accuracy  
- Deploy the model as an API or dashboard  
