# Stock Price Prediction Based on TimesNet

## Data Collection

The stock data is collected using the open-source financial interface AkShare, retrieving relevant stock market data. The dataset used in this project originates from East Money (东方财富网) - Market Homepage - Shanghai, Shenzhen, and Beijing A-Shares - Daily Market Data.

![image](https://github.com/user-attachments/assets/014c2180-3d20-4d44-bd59-144f03ce159c)


## Data Preprocessing

Data Cleaning: Handling missing values, outliers, and duplicate data.

Data Transformation: Standardization, normalization, and encoding categorical variables.

Feature Engineering: Creating new features, selecting important features, and performing dimensionality reduction.
![image](https://github.com/user-attachments/assets/81026575-d11b-4070-8d92-1797a8e10ea8) ![image](https://github.com/user-attachments/assets/f62e2ffc-5f20-4989-aa68-bf100c8b0a3b)




## Model Training and Evaluation

The model is trained using the training dataset, while validation and test datasets are used to assess performance. The evaluation metrics used include:

Mean Absolute Error (MAE)、Mean Squared Error (MSE)、Root Mean Squared Error (RMSE)、Mean Absolute Percentage Error (MAPE)、Mean Squared Percentage Error (MSPE)

This project leverages TimesNet（https://github.com/thuml/Time-Series-Library） for time-series stock price prediction, focusing on accurate market trend forecasting. If you want to know more about the model, please refer to the Timesent official documentation.
