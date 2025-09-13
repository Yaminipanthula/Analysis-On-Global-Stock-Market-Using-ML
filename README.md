Analysis_on_Global_Stock_Market_Using_ML

Global Stock Market Analysis using Machine Learning
This project applies various Machine Learning algorithms to analyze and predict global stock market performance.
It involves data preprocessing, exploratory data analysis (EDA), model building, and performance comparison to determine the best-fit models for forecasting stock market trends.

PROJECT OVERVIEW  
Dataset: Daily trading records from multiple global stock exchanges.
Target Variable: PortfolioOpen (value of portfolio at start of trading day).
Features: Stock indices (NIFTY50, S&P 500, FTSE100, Hang Seng), commodity prices (Gold, Brent), cryptocurrency (BTC/INR), bond yields, and currency exchange rates (USD/INR, GBP/INR).

OBJECTIVE:
Clean and preprocess raw stock data
Explore correlations and insights using EDA
Apply different ML models to predict PortfolioOpen
Identify the best performing model

Data Preprocessing
Dropped unnecessary columns (e.g., trading dates).
Handled missing values using median imputation.
Treated outliers with the IQR method.
Converted categorical/object datatypes into numerical format.
Checked for multicollinearity using VIF and dropped high-VIF features.

Exploratory Data Analysis (EDA)
Line Plots: Trends over time
Scatter Plots: Relationships between variables
Histograms: Distribution of features
Pairplots: Multi-variable comparisons
Correlation Heatmap: Strong correlations identified (e.g., PortfolioOpen vs. PreviousPortfolioClose)

Best Model Performance
The Gradient Boosting Regressor achieved the highest accuracy:

R² Score: 0.9580 (80:20 train-test split)
MAPE: 0.0110
This makes Gradient Boosting Regressor the most suitable model for predicting PortfolioOpen.

FUTURE SCOPE:
Incorporate more global datasets for better generalization.
Use real-time stock market data for live prediction.
Improve accuracy using feature engineering and deep learning.
Build applications for portfolio management and market trend prediction.
