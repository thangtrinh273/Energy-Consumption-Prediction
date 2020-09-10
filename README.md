# Energy-Consumption-Prediction
Household Energy consumption prediction using ARIMA model. 

I used Auto Regressive Integrated Moving Average (ARIMA) model for predicting the energy consumption of UK household. 
The data was found online. 
Before I decided to use ARIMA as the main model for the availabled data, I had tried Support Vector Machine (SVM) and deep learning model: long-short term memories (LSTMs). The output predictions from other models except for ARIMA were not quite acurate. The reason for that might be the nature of the problem (energy consumption predition), which is a "complete" stochastic.
The conclusion after complete this project is: complex models might not perform as well (because data points are quite small for 1 household) as suitable machine learning model. Sometimes just by moving along the average can give you the good results and ofcourse it has to base on Educated Guessing Direction.
