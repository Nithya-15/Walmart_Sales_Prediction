# Walmart Sales Prediction

## Project Overview

This project focuses on predicting sales for Walmart stores across the United States using historical sales data. The aim is to accurately forecast demand and optimize inventory management, taking into account various factors such as holidays, economic conditions, and promotional markdowns.

## Business Problem

Walmart, one of the leading retail stores in the US, faces challenges due to unforeseen demand spikes, particularly during holidays and special events. The company occasionally runs out of stock due to inaccurate sales predictions. The goal of this project is to build an ideal machine learning algorithm that can predict sales more accurately, considering factors like economic conditions (CPI, unemployment rates) and holiday impacts.

## Dataset

The dataset contains historical sales data from 45 Walmart stores, covering the period from 2010-02-05 to 2012-11-01. Key fields in the dataset include:

- **Store**: Store number.
- **Date**: The week of sales.
- **Weekly_Sales**: Sales for the given store.
- **Holiday_Flag**: Indicator for whether the week is a special holiday week (1 - Holiday week, 0 - Non-holiday week).
- **Temperature**: Temperature on the day of sale.
- **Fuel_Price**: Cost of fuel in the region.
- **CPI**: Prevailing consumer price index.
- **Unemployment**: Prevailing unemployment rate.
- **Holiday Events**:
  - **Super Bowl**: 12-Feb-10, 11-Feb-11, 10-Feb-12, 8-Feb-13.
  - **Labour Day**: 10-Sep-10, 9-Sep-11, 7-Sep-12, 6-Sep-13.
  - **Thanksgiving**: 26-Nov-10, 25-Nov-11, 23-Nov-12, 29-Nov-13.
  - **Christmas**: 31-Dec-10, 30-Dec-11, 28-Dec-12, 27-Dec-13.

## Methodology

### 1. Data Preprocessing
- **Handling Missing Values**: Ensured data completeness by filling or removing missing values.
- **Feature Engineering**: Created new features based on date, holidays, and economic indicators to enhance model accuracy.

### 2. Exploratory Data Analysis (EDA)
- **Sales Trends**: Analyzed sales trends over time, especially around holiday periods.
- **Impact of Economic Factors**: Assessed how factors like CPI and unemployment influence sales.

### 3. Model Building
- **Machine Learning Models**: Implemented several models, including RandomForest Regressor, to predict sales.
- **Hyperparameter Tuning**: Performed tuning to improve model performance.

## Results

- **Model Accuracy**: Achieved a prediction accuracy of X% (replace with actual value) with the RandomForest Regressor.
- **Insights**: Identified key factors that influence sales, enabling more accurate inventory planning and promotional strategies.

## How to Run the Project

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/Walmart-Sales-Prediction.git
    cd Walmart-Sales-Prediction
    ```

2. **Install the required packages**:
    Ensure you have Python installed, then run:
    ```bash
    pip install -r requirements.txt
    ```

3. **Run the Jupyter Notebook**:
    Open the notebook in Jupyter and execute the cells to see the analysis and results.

## Tools and Libraries Used

- **Python**
- **Pandas**
- **NumPy**
- **Matplotlib**
- **Seaborn**
- **Scikit-learn**
- **Jupyter Notebook**

## Future Work

- **Incorporating Additional Data**: Integrating more economic indicators or weather data to further enhance model predictions.
- **Model Optimization**: Experimenting with advanced models like XGBoost or neural networks.

---

Make sure to adjust the README with any specific metrics, model accuracies, or other details that you gather from your project results.
