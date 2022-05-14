# Linear-Models

#### 1. Exponential Regression

Modelling bacteria using exponential regression. This is done by transforming the exponential data into linear data using $\ln(\cdot)$, after which regular linear regression techniques can be used. Regressing based on temperature and humidity a $R^2 = 78 \%$ is obtained. An important task of regression is to check the validity of the linear regression assumptions pertaining to the residuals. 

* Residulas have constant variance
* Residulas are independent
* Resiudals are normally distributed

The residual analysis was performed with graphical methods, although, more sophisticated statistical tests for normality and correlation could be useful.

<p align="center">
<img width="1174" alt="image" src="https://user-images.githubusercontent.com/62723280/168441882-08d79473-3a34-4767-966e-7c336aa2df27.png">
<\p>

Next, confidence and prediction bands were calculated for the regression model as shown below. The confidence interval gives a range of possible models, $\mathbb{E}[Y]$, that could be fit depending on the sample of the population. The prediction interval gives a range of possible values for a new observation $Y$. Note the difference between the two.
