**Deep Recurrent Factor Model (LSTM + LRP)**


This repository contains an implementation of the Deep Recurrent Factor Model, an interpretable non-linear and time-varying multi-factor model based on LSTM and Layer-wise Relevance Propagation (LRP). The model extends traditional linear multi-factor models by capturing non-linear relationships and time dependencies between factors and stock returns, while preserving interpretability for institutional investment practice.



**Features**

Non-linear, time-varying factor modeling using bidirectional LSTM

Interpretability via Layer-wise Relevance Propagation (LRP) to linearize LSTM outputs

Baseline comparisons with linear regression, SVR, Random Forest, and fully-connected DNN

Sliding-window training and monthly forecasting

Performance metrics: MAE, RMSE, annualized return, volatility, Sharpe rati

**Model Architecture**

Deep Recurrent Factor Model (LSTM + LRP):

Bidirectional LSTM with hidden size = 16, sequence length = 5

LRP approximation to obtain time-varying factor coefficients β

Comparison Models:

Linear Regression (scikit-learn)

Support Vector Regression (SVR)

Random Forest Regressor

Deep Factor Model (fully-connected DNN)

Deep Factor Model + LRP

