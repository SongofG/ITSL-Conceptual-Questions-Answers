# Chapter 2: Statistical Learning

## Question 1

(a) **Better**; there are large number of sample to train the model, and since there is no/less assumption about the true $f$, flexible model will be better

(b) **Worse**; there is a danger of overfitting, and since data is not enough, the model may end up not learning enough and therefore fail to estimate the true $f$. Since model is flexible, it may decrease the bias, but could possibly introduce huge variance, end up having large MSE in the testing dataset.

(c) **Better**; because the relationship between predictors and response variable is highly non-linear, it may be difficult to model the true relationship $y = f(x)$ by a set of assumptions. Flexible models will be more suitable in this case.

(d) **Worse**; without any prevention of overfitting and enough sample size, high variance of the error term $\epsilon$ will make it harder for the flexible model to capture the original relationship $y = f(x)$.

## Question 2

(a) **Regression**, **inference**, $n=500, p=3$

(b) **Classification**, **Prediction**,$n=20, p=13$

(c) **Regression**, **Prediction**, $n=52, p=3$

## Question 3
(a) ![Question 3, a](/Chapter%202%20-%20Statistical%20Learning/images/Q3.jpeg)