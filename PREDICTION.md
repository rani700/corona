# Predictions

Our Model predicts the next day possible cases based on the given previous n days cases.  
Here N is varied from 10 to 20 to see which model gives the best results.  
The results are summarised below.  

<hr>

| N       | Score 			 | MSE 				| Accuracy Graph | Forecasting Graph | Cases on 14 April |
|---------|------------------|------------------|----------------|-------------------|-------------------|
| 10 Days |0.99877|63.407 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/10.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/10.png" >                   |20545				 |
| 11 Days |0.99882|61.675|<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/11.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/11.png" >                   |19801				 |
| 12 Days |0.99883|62.132|<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/12.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/12.png" >                   |20056				 |
| 13 Days |0.99896|55.673 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/13.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/13.png" >                   |18380				 |
| 14 Days |0.99896|56.237|<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/14.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/14.png" >                   |18423				 |
| 15 Days |0.99936|35.262 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/15.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/15.png" >                   |18778				 |
| 16 Days |0.99940|33.339 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/16.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/16.png" >                   |18725				 |
| 17 Days |0.99941|33.026 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/17.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/17.png" >                   |18824				 |
| 18 Days |0.99944|31.746|<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/18.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/18.png" >                   |18428				 |
| 19 Days |0.99950|28.802 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/19.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/19.png" >                   |17399				 |
| 20 Days |0.99965|20.694 |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/accuracy/20.png" >                |<img src="https://raw.githubusercontent.com/rani700/corona/master/screenshots/regression/forecasting/20.png" >                   |15298				 |
