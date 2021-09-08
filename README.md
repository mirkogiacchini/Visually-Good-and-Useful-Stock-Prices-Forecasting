# Visually-Good-and-Useful-Stock-Prices-Forecasting

Final project for the Deep Learning and Applied Artifical Intelligence course ([https://github.com/erodola/DLAI-s2-2021]).

We considered the problem of predicting the next stock price of an asset from the sequence of previous prices. We observed that using the actual stock prices as data prior we are able to predict the general trend of the prices but the predictions are not so good when used as part of a trading strategy, viceversa using the differences of adjacent prices gives good models for the trading strategy but with bad predictions for the actual prices. We propose a loss function that attempts to take the best out of these two strategies.
