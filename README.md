## LSTM Model for Stock Market Price Prediction

This repository contains a Jupyter Notebook that implements an LSTM-based model to predict stock market prices using historical data fetched from Yahoo Finance. The model utilizes data preprocessing, moving averages, and neural network techniques to forecast future prices.

### Key Features
- **Data Preparation**: Fetches historical data from Yahoo Finance and processes it for analysis.
- **Visualization**: Includes moving averages and other key metrics to visualize trends.
- **Model**: Implements an LSTM model for prediction.
- **Evaluation**: Calculates metrics like Mean Absolute Error and R² score to assess performance.
- **Prediction**: Compares actual vs. predicted prices on test data.

### Libraries Used
- `pandas` and `numpy`: For data manipulation and numerical computations.
- `matplotlib`: For plotting and visualization.
- `yfinance`: To fetch stock market data.
- `sklearn`: For data scaling and evaluation metrics.
- `tensorflow`: For building and training the LSTM model.
- `datetime`: For handling date-related operations.

### Notebook Structure
1. **Data Loading**: Fetches historical stock data.
2. **Visualization**: Plots closing prices and moving averages.
3. **Data Preprocessing**: Splits data into training and testing sets and normalizes it.
4. **Model Training**: Builds and trains an LSTM model.
5. **Testing and Evaluation**: Makes predictions and evaluates performance using error metrics.
6. **Results Visualization**: Compares actual and predicted values.

### How to Use
1. Clone this repository:
   ```bash
   git clone https://github.com/your-repo/LSTM-stock-prediction.git
   ```
2. Install the required libraries:
   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook and run all cells:
   ```bash
   jupyter notebook LSTM_model_for_stock_market_price_prediction.ipynb
   ```

### Output
The model produces a comparison graph of predicted vs. actual prices, along with performance metrics.

---
