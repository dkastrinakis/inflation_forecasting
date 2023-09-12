# inflation_forecasting
Inflation forecating in Greece: A comparison between ARIMA, XGBoost and LSTM.

## Abstract

Inflation has been plaguing societies since the ancient times, at occasions leading to complete market instability and significantly dropping the living standards of people in societies. In less severe scenarios, inflation adds uncertainty to investment decisions and shortens the investment horizon in emerging markets, making the generation of accurate inflation forecasting models imperative.
This paper seeks to compare three different widely used approaches in the domain of macroeconomic forecasting in determining which one of those approaches shows more promising results for short term inflation prediction. More specifically, the first method that is employed to forecast inflation is ARIMA, an extensively used, traditional, time series forecasting approach that focuses solely on past CPI values to generate predictions. Moreover, an LSTM Artificial Neural Network has been designed to forecast inflation, as a contemporary deep learning approach often used for regression tasks and time series forecasting. Finally, XGBoost, an ensemble algorithm that combines simple decision trees (base learners) is the third model that has been generated, which is the proposed method for inflation forecasting in this research project. All three methods are compared to a persistence model, which constitutes a challenging baseline to surpass in terms of its forecasting performance.
Findings show that, overall, XGBoost outperformed both the ARIMA and the LSTM ANN in terms of forecasting performance (RMSE). The ARIMA model demonstrated better performance than that of the LSTM, showcasing that simpler models may be more effective when working with only a limited amount of data. However, it should be highlighted that the LSTM model showed promising results in capturing unexpected inflation dynamics, particularly during extreme scenarios. On the other hand, although XGBoost exhibited the smallest RMSE score and most accurately predicted the direction of CPI changes, the model was completely unable to capture the extreme inflation spikes that occurred after 2022. The persistence baseline, although it exhibited the best results in terms of RMSE, it does not capture at all the direction of changes in CPI values, and hence its reliability as a forecasting model is compromised.

## NOTE

* This project was completed as part of my Business Analytics MSc dissertation project at Aston University.
* The full report can be provided upon request.
