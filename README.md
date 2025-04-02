Stock Price Prediction using Machine Learning
=============================================

Overview:
---------
This project predicts stock prices using a machine learning model. 
The dataset contains historical stock data for multiple companies, and the model leverages technical analysis and machine learning to forecast future prices.

Features:
---------
- Load and preprocess stock data from CSV
- Perform feature engineering (Daily Returns, Moving Averages, etc.)
- Visualize stock price trends over time
- Train a Random Forest Regressor for stock price prediction
- Evaluate model performance using Mean Squared Error (MSE)

Technologies Used:
------------------
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Statsmodels (for time series analysis)
- Scikit-learn (for machine learning)

Installation:
-------------
1. Clone the repository:
   git clone https://github.com/dhanunjaireddy07/stock_prediction.git
   cd stock_prediction

2. Install dependencies:
   pip install -r requirements.txt

3. Run the Jupyter Notebook:
   jupyter notebook stock.ipynb

Dataset:
--------
- The notebook uses a dataset named `stocks.csv` which should contain historical stock price data.
- Ensure the dataset is placed in the same directory as the notebook.

Results:
--------
- The model provides insights into stock price movements based on historical trends.
- Performance is evaluated using the Mean Squared Error (MSE) metric. 
