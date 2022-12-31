# Yes-Bank-Closing-Price-Prediction
Almabetter Capstone Project of Yes bank price prediction.
Capstone Project -Supervised Learning (Regression) Our problem statement -Yes Bank is a well-known bank in the Indian financial domain. Since 2018, it has been in the news because of the fraud case involving Rana Kapoor. Owing to this fact, it was interesting to see how that impacted the stock prices of the company and whether Time series models or any other predictive models can do justice to such situations. This dataset has monthly stock prices of the bank since its inception and includes closing, starting, highest, and lowest stock prices of every month.


![yes-bank-share-price-target (1)](https://user-images.githubusercontent.com/113955196/210153180-a3947bcf-00d3-4b11-b14c-9ab6f094f03f.jpg)



Our main motive of the project was to predict the stock's closing price of the month. To determine the YES bank's stock’s future value on the national stock exchange. The advantage of a successful prediction of a stock's future price could results insignificant profit. The efficient-market hypothesis recommends that stock costs mirror all right now accessible data and any value changes that are not founded on recently uncovered data subsequently are an unpredictable. We have to build model which help us to predict the future stock prices. The stock market is known for being volatile, dynamic, and nonlinear. Accurate stock price prediction is extremely challenging because of multiple (macro and micro) factors, such as politics, global economic conditions, unexpected events, a company’s financial performance, and so on. But, all of this also means that there’s a lot of data to find patterns in. So, financial analysts, researchers, and data scientists keep exploring analytics techniques to detect stock market trends. This gave rise to the concept of algorithmic trading which uses automated, pre-programmed trading strategies to execute orders.

The Challenge we face is due to small dataset so it’s difficult to get good model accuracy

In EDA part we observed that

1)There is increase in trend of Yes Bank's stock's Close price till 2018 and then sudden decrease.
2)There is increase in trend of Yes Bank's stock's Open price till 2018 and then sudden decrease.

3)We observed that open vs close price graph concluded that after 2018 yes bank's stock hitted drastically.

implementing all model we get accuracy.

1)Linear regressor with highest accuracy - 99.2%

2)Ridge regression accuracy - 99.23%

3)Lasso regression accuracy - 99.28%

4)ElasticNet accuracy - 96.89%

5)Decision tree regressor accuracy - 97.64%

6)Random Forest accuracy - 98.50

7)Gradient Boost accuracy - 98.33

8)Xtream Gradient Boost accuracy - 98.45

Overall, we can say that Linear Regressor is the best model among all regression model which gives around 99.28% accuracy of predicting stock price of our dataset.
