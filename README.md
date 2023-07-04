Problem Statement

Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month. The main objective is to predict the stock’s closing price of the month.

Business objective:

Yes bank is private bank and it has many stake holders , so its matter that the stocks they own and price of their stocks . It’s very necessary to them to know the stock they own and price of the stock. So they could make decisions about the selling or keeping then stock and know how much the business is get affected by the inflation of the stock price.

Inforamtion About the data:

We have Yes Bank monthly stock price dataset. It has following features (Columns):

1)Open: Opening price of the stock of particular month.

2)High: It is the highest price at which a stock traded during a given month period.

3)Low: It is the lowest price at which stock traded during a given month period.

4)Close: Closing price stock at the end of a Trading month.

5)Date:In which month and Year is given with respect the stock.

Conclusion

1.At first we do the data wrangling then data cleaning and data transformation after that we do the Modeling part.

2. The trend of the price of Yes Bank's stock increased until 2018 and then Close,Open,High,Low price decreased.

3. Based on the open vs. close price graph, we concluded that Yes Bank's stock fell significantly after 2018.

4. Visualization has allowed us to notice that the closing price of the stock has suddenly fallen starting in 2018. It seems reasonable that the Yes Bank stock price was significantly impacted by the Rana Kapoor case fraud.

5. High, Low, Open are directly correlate with the Closing price of stocks.

6. The target variable is highly dependent on input variables.

7. Linear Regression has given the best results with lowest MAE, MSE, RMSE and MAPE scores.

8. Ridge regression shrunk the parameters to reduce complexity and multicollinearity, but ended up affecting the evaluation metrics.

9. Lasso regression did feature selection and ended up giving up worse results than ridge which again reflects the fact that each feature is important (as previously discussed).

10. The accuracy for each model is more than 90%.


