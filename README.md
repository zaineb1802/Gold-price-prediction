Gold price prediction

This project aims to predict the price of gold using various economic indicators and commodity prices. It uses historical data stored in an Excel file and applies machine learning techniques to build a regression model for gold price prediction.

## Features Used

The dataset includes:
- Commodity Prices: Gold, Silver, Oil, Natural Gas, Wheat, Coffee (Robusta and Arabica)
- Economic Indicators: Unemployment Rate, Industrial Production, CPI, Exports, Imports, External Reserves, EUR/USD exchange rate
- Market Indices: NASDAQ, S&P 500, Dow Jones
- Personal Metrics: Personal Income, Personal Consumption Expenditures

## Project Workflow

1. **Data Preprocessing**:
   - Handled missing or inconsistent data
   - Converted monetary values from strings to numeric
   - Normalized or scaled features if needed

2. **Exploratory Data Analysis (EDA)**:
   - Correlation analysis between gold price and other indicators
   - Visualization of trends and relationships

3. **Model Building**:
   - Used regression models (e.g. Linear Regression, Random Forest, etc.)
   - Evaluated models using metrics like R² and RMSE

4. **Prediction & Visualization**:
   - Predicted gold prices based on selected features
   - Compared predicted vs actual prices using plots

## Tools & Technologies
   - Python (Jupyter Notebook)
   - Pandas, NumPy
   - Scikit-learn
   - Seaborn, Matplotlib
   - JupyterLab / VS Code
