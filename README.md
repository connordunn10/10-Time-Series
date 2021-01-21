# 10-Time-Series

Yen Futures Time Series Conclusion
====================================

Based on your time series analysis, would you buy the yen now?
It is risky due to volitility, but I would not buy. While the Yen/USD is increasing in price (ARIMA model), the returns forecast are diminishing (ARMA), but both are not significant due p-values greater than .05. 

Is the risk of the yen expected to increase or decrease?
The risk is expected to increase, because the GARCH model, showing volitility, is increasing.

Based on the model evaluation, would you feel confident in using these models for trading?
I would not use the ARMA or ARIMA models because their their p-values are greater than .05 (p>.05) The GARCH model predicts the amount of volitility of the yen's future prices. Yen future price volitility is increasing, and it is significant due to a p<.05. Volitility is typically a good indicator for trading derivatives, therefore the GARCH model would be the better option among the models.

Regression Analysis Conclusion
====================================

The Out-of-Sample data is the Testing data, in which the model has NOT seen before. The Out-of-Sample Root Mean Squared Error (RMSE) to the thousandth is 0.415.

The In-Sample data is the Training data, in which the model has seen before. The In-Sample Root Mean Squared Error (RMSE) rounded to the thousandth is integ is 0.566.

Usually, the RMSE is lower for the training data. The training data(In-Sample data) is higher than the test data(Out-of-Sample) in this case. The testing data(Out-of-Sample), which the the model has not seen before, performs better than the training data(In-Sample).
