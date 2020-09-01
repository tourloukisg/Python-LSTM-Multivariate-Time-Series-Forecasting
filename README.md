# Python-LSTM-Multivariate-Time-Series-Forecasting

The first part of this demonstration (PART A) is focused on data preparation/manipulation of the imported dataset features('.txt' file format) to apply basic data preprocessing/cleaning methods by converting the dataset into a dataframe (pandas). In addition, an exploratory analysis is presented to highlight key aspects of each selected 'Electric Power Consumption' dataset feature past (time series) behavior, so as to get meaningful insights with respect to its distribution, correlations with the other examined features, its behavior when grouped at different time periods and the change of its statistical properties over time.

The scope of the second part of this project (Part B) is to demonstrate the use of the LSTM model for multivariate time series forecasting. A new dataset is created that consists of four dataset features (Global Active Power, Global Reactive Power, Global Intensity and Voltage) grouped my their mean (average) weekly values. These features are to be split into two sets (training and test) so as to use their past observations as inputs to the deep learning model in order to investigate the LSTM predictive capabilities by training this deep learning neural network with 4 years of past average weekly values of the aforementioned dataset features to predict their average weekly values for the next 52 weeks (prediction horizon of 1 year). The evaluation of the LSTM model performance for the cases where the prediction horizon is known is based on the comparison of the forecasted values with the test(actual/target)values (Performance Metric --> Root Mean Squared Error).

The Dataset (.txt file format) for this project has been obtained from Kaggle:

"Household Electric Power Consumption" -- File: "household_power_consumption.txt" -- Source: https://www.kaggle.com/uciml/electric-power-consumption-data-set
