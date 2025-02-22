# Demand-Forecasting-and-Price-Optimization


This project focuses on optimizing demand forecasting and price optimization using machine learning techniques. It integrates models like XGBoost and LightGBM to predict sales and applies optimization techniques to recommend the best pricing strategies. The project starts by analyzing sales data and building a predictive model to forecast future demand for various products. Using the predictions, a price optimization model is created to find the optimal price for each product. The model takes into account various factors such as cost, competitor prices, and historical demand to maximize profit.

## Dataset
The dataset used in this project is sourced from Kaggle. It contains detailed product sales data including product information, sales quantities, prices, and competitor prices. This data is cleaned and preprocessed for analysis and training the machine learning models.

## Features

- Data preprocessing and feature engineering
- Demand forecasting using XGBoost and LightGBM
- Hyperparameter tuning with GridSearchCV and RandomizedSearchCV
- Price optimization using PuLP
- Performance evaluation with metrics like RMSE and R-squared

## Installation

1. Clone the repository
   ```
   git clone https://github.com/Demand-Forecasting-and-Price-Optimization
.git


3. Run the main script in jupyter notebook

## Usage

1. Source the dataset with required features like sales history, pricing, promotions, and competitor prices.
2. Train the demand forecasting model to predict future sales.
3. Use the optimization module to generate the best price recommendations.
4. Evaluate the results and adjust parameters as needed.


## Requirements

- Python 3.8+
- Pandas
- NumPy
- Scikit-learn
- XGBoost
- LightGBM
- Random Forest
- Seaborn
- PuLP


## License

This project is open-source and available under the MIT License.


