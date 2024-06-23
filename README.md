# Yes Bank Stock Price Prediction

## Project Summary 

This project aims to predict the monthly closing stock price of Yes Bank using historical stock price data. The dataset contains information about Yes Bank's stock prices from its inception, with a total of 185 rows and 5 columns: Date, Open, Close, High, and Low.

The dataset is analyzed through various data wrangling techniques, feature engineering, and exploratory data analysis (EDA). Multiple regression models are applied to determine the best model for predicting the closing price of the stock.

Business Objective

Yes Bank is a well-known private bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. This project investigates the impact of this event on the stock prices and aims to predict the stock’s closing price of the month. Accurate predictions will help stakeholders make informed decisions about their investments.

General Guidelines
Well-structured, formatted, and commented code.

Exception Handling, Production Grade Code & Deployment Ready Code.

At least 15 logical and meaningful charts with insights.

Table of Contents
Installation
Use the of Project
Data Structure
Data Wrangling
Exploratory Data Analysis
Modeling Process
Results
Contributing

Installation

python -m pip install pip==17.0

To Install numpy :- pip install numpy

To install pandas:- pip install pandas

Use of the Project

![image](https://github.com/mintijha/Yes-Bank-Stock-Closing-Price-Prediction/assets/123978172/a66c93c5-f5c0-4fd9-91e3-2765515cda64)

From this insight we also grab full range of close price among different years which helps us to analize market information.

![image](https://github.com/mintijha/Yes-Bank-Stock-Closing-Price-Prediction/assets/123978172/1044ac23-a872-44b2-9e70-2a8ddd88b86d)

gained insights can help create a positive business impact by identifying trends in the data. For example, the high average closing price in January suggests that the business did well that month. The low average closing price in February suggests that the business may have experienced some challenges during that month. However, the overall trend is positive, which suggests that the business is on track to achieve its goals. There are no insights that lead to negative growth.

![image](https://github.com/mintijha/Yes-Bank-Stock-Closing-Price-Prediction/assets/123978172/cd38da12-628f-45c2-8e29-b6264816a8ec)

Yes, it will make a postive impact because we can see the simlar trend of price on this stock so it will helpful to make decision in near future.




Dataset Information
The dataset contains the following features:

Date: Month and year of the stock data.
Open: Opening price of the stock for the month.
High: Highest price at which the stock traded during the month.
Low: Lowest price at which the stock traded during the month.
Close: Closing price of the stock at the end of the month.


Data Wrangling
Changing date column datatype to datetime format.
Creating separate columns for month and year from the date column for better visualization.

Modeling Process
Train-Test Split: Dataset split into 80% training and 20% testing.

Models Applied:

Linear Regression
Ridge Regression
Lasso Regression
Model Evaluation:

Linear Regression provided the best performance based on MAE, MSE, RMSE, and MAPE scores.

Results
Linear Regression: Best performance with lowest errors.
Ridge Regression: Reduced multicollinearity but negatively impacted evaluation metrics.
Lasso Regression: Performed feature selection but had higher errors than Ridge.

Contributing

Amit Yadav :- https://github.com/Amit6124


