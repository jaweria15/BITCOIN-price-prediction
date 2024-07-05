# BITCOIN-price-prediction
## Project Description: Time Series Forecasting for Bitcoin Prices Using LSTM

This project demonstrates how to build and train a Long Short-Term Memory (LSTM) neural network to predict Bitcoin prices using historical data. The dataset spans from 2019 to 2024 and includes various stock metrics such as opening, closing, high, and low prices. The goal is to predict future Bitcoin closing prices and visualize the accuracy of the model against actual historical prices.

### Key Components

1. **Data Exploration and Preprocessing**:
   - Load and inspect the dataset using pandas and `ydata_profiling` for a detailed data profile.
   - Handle date formatting and filter data to specific time frames.
   - Visualize trends over the entire period and on a month-by-month basis.
   - Normalize data for model training using MinMaxScaler.

2. **Visualization**:
   - Use Plotly to create interactive line plots for visualizing trends and comparisons.
   - Plot the overall Bitcoin price data and the filtered time frame used for model training.

3. **Model Building**:
   - Prepare the dataset for LSTM by creating time series sequences.
   - Build and compile an LSTM model with a dense output layer.
   - Train the model using the training data and validate it on the test data.

4. **Model Evaluation**:
   - Evaluate the model using RMSE, MSE, MAE, explained variance score, and R² score.
   - Compare the model's predictions against actual values to assess performance.

5. **Result Visualization**:
   - Plot the training and validation loss to monitor overfitting.
   - Visualize the comparison between the predicted and actual closing prices.

### Dependencies

- `pandas`
- `numpy`
- `ydata_profiling`
- `matplotlib`
- `plotly`
- `sklearn`
- `tensorflow`

### Usage

This project is designed for those interested in time series forecasting and neural network models. It provides a complete pipeline from data preprocessing to model evaluation and visualization, which is useful for learning and applying LSTM networks in financial predictions.
To better understand this code, download the code file along with the dataset file and run it in your Jupyter Notebook.

https://github.com/jaweria15
You can feel free to contribute or raise any other issues for further improvements.
