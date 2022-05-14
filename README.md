# Linear-Models

#### 1. Exponential Regression

Modelling bacteria using exponential regression. This is done by transforming the exponential data into linear data using $\ln(\cdot)$, after which regular linear regression techniques can be used. Regressing based on temperature and humidity a $R^2 = 78 \%$ is obtained. An important task of regression is to check the validity of the linear regression assumptions pertaining to the residuals. 

* Residulas have constant variance
* Residulas are independent
* Resiudals are normally distributed

The residual analysis was performed with graphical methods, although, more sophisticated statistical tests for normality and correlation could be useful.

<p align="center">
<img width="1174" alt="image" src="https://user-images.githubusercontent.com/62723280/168441920-6acfe31c-ba63-4501-8ee3-91c51008a3fb.png">
<\p>

Next, confidence and prediction bands were calculated for the regression model as shown below. The confidence interval gives a range of possible models that could be fit depending on the sample of the population. The prediction interval gives a range of possible values for a new observation. Note the difference between the two.
 <p align="center">
  <img width="696" alt="image" src="https://user-images.githubusercontent.com/62723280/168441948-2614de91-e806-4359-8e53-91305102a746.png">
<\p>
