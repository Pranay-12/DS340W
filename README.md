# DS340W-Midterm
We are conducting a four step machine learning based approach to optimizing a stock portfolio

First Step: Stock Index Selection

Second Step: Stock Selection

Third Step: Correlation Analysis

Fourth Step: Portfolio Construction Using Visualization

For the third step (correlation analysis) of our four step method we use the model developed by Hyeong Kyu Choi, for the research visit: https://arxiv.org/pdf/1808.01560v5.pdf

The code for our third step of correlation analysis is from: https://github.com/imhgchoi/ARIMA-LSTM-hybrid-corrcoef-predict 
We made some modifications it.

# What You'll Find In Each Folder
### Step 1 - Stock Index Selection
1. Stock Indexes Data: Data used to train the stock index prediction model
2. Linear Regression.ipynb: Baseline stock index prediction model
3. StockIndexPrediction.ipynb: Hybrid stock index prediction model and stock index selection criteria

### Step 2 - Stock Selection
1. Defensibility.xslx: Analysis of market crash data for stock index selection

### Step 3 - Correlation Analysis
1. Random_Stocks: Data used for correlation analysis for random stock portfolio
2. Random_Stocks_Results: Correlation analysis results for random stock portfolio
3. Selected Indexes: Data for stock indexes of selected stocks to aid correlation analysis
4. Selected_Stocks: Data used for correlation analysis for selected stock portfolio
5. Selected_Stocks_Results: Correlation analysis results for selected stock portfolio
6. ARIMA Model.ipynb: ARIMA model part of hybrid model
7. DATA_PREPROCESSING.pynb: Data preparation for hybrid model
8. LSTM Model.ipynb: LSTM model part of hybrid model
9. Random_Portfolio.ipynb: Randomly generated number to pick random subset of stocks for our random portfolio as decribed by our parent paper
10. epoch247.h5: Trained LSTM model from parent paper

### Step 4 - Portfolio Construction Using Visualization
1. Correaltion Results: Correlation Analysis results from step 3 for both random and selected portfolios
2. correlation_heatmap.ipynb: Visualization of correlation analysis and final portfolio is chosen

### Testing
1. Top_5_Random_Stocks: Stock data for the final random stock portfolio
2. Top_5_Selected_Stocks: Stock data for the final selected stock portfolio
3. Testing.ipynb: Testing to determine effectiveness of our four-step portfolio optimization approach
