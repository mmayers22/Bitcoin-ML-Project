# Bitcoin-ML-Project

## Intro
This was one of my first big personal projects involving data science and analysis in Python. The goal of this analysis was to see how other currencies  and materials affected the price of Bitcoin, and then run some popular machine learning algorithms to try and predict when Bitcoin prices will rise or fall. Bitcoin is known to be very unpredictable and non-reliant on other currencies or stock market values, which made this project a big challenge for me. Analysis was done using Python and heavily relied on the pandas and scikit-learn packages, and all code was developed in a Jupyter Notebook. Source code and more in-depth notes about the process can be found in the main project folder at BTC_ML_Project.ipynb

## Variables
Variables used to predict Bitcoin price changes include several currencies' value against the US Dollar including the Canadian dollar, Euro, Swiss Franc, British Pound, and Yen; additionally, price change in oil, gold, and the S&P 500. 

## Results
The ADA boost classifier was the most successful algorithm for predicting an increase or decline in Bitcoin price, although all of the regression models were quite far off. The ADA boost classifier correcly predicted whether Bitcoin would rise or fall over a one month period of test data with 78% accuracy. With the unpredictable nature of Bitcoin, this is a very high accuracy score, however the model would likely lose accuracy over a longer period of time, as Bitcoin price is largely independent of other more conventional investments and currencies. 

## Future Refinements
This model could likley be refined much more and include more helpful predictors, and it would be interesting to see how other cryptocurrencies can be used to predict rises or falls in Bitcoin prices. 

## Real-World Applications
This model could be used to buy and sell Bitcoin on days when it predicts a rise or fall respectively, but due to the nature of the classification model it  does not factor in the amount of increase or decrease, which makes it somewhat unreliable for consistency. Another factor to take into account is transaction and processing fees that typically are charged when a Bitcoin transaction is made, which would cut into the profits made using this strategy. A more refined model with lower error on regression testing would be much more helpful in Bitcoin trading strategy, but the current predictors used in this project are not enough to confidently predict these gains and losses. 
