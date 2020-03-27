# corona
Corona Fatalities Prediction using time series forecasting.

## Datasets
I have used this dataset https://github.com/rani700/corona/blob/master/datasets/train.csv which provides the Confirmed cases and Fatalities per day starting from 22nd january till 18th march by the location of the world.

## Visualisation
https://github.com/rani700/corona/blob/master/visualisation.ipynb  
Here you can find the visualisation of the Fatalities and Confirmed cases plotted on the world map.

## Predictions 
  
As we have limited data. And any deep learning model needs large dataset to build some useful model.
I have used the VLSW for generating the large time series data from the smaller dataset which can be used for traing the deep learning Model.

### Univariate Prediction (Predicting New cases)

<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/case_prediction.png">

https://github.com/rani700/corona/blob/master/ssim_prediction.ipynb  
Here I have trained Univariate prediction model with SSIM Model which contains 2 LSTM layers, 1 Dense Layer, 1 attention mechanism.
Using this model I achieved the validation <b>loss of 0.0072</b> and Validation <b>accuracy of 0.9048</b>  
  
Here given previous 10 days Confirmed cases this model can predict the possible cases in the next 5 days.

### MultiVariate Prediction (Predicting Fatalities)

<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/fatalities_prediction.png">

https://github.com/rani700/corona/blob/master/ssim_prediction_multivariate.ipynb  
Here I have trained MultiVariate prediction model with SSIM Model which contains 2 LSTM layers, 1 Dense Layer, 1 attention mechanism.
Using this model I achieved the validation <b>loss of 0.0011</b> and Validation <b>accuracy of 0.9563</b>  
  
Here given previous 10 days Confirmed cases and Fatalities this model can predict the possible cases in the next 5 days.



<b>*Note :-</b> These models are trained for the China Data. But this model can be built for any Country. Also model feasibility can be modeled according to the need.




