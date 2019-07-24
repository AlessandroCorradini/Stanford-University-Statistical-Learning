# Chapter 7 Quiz

## 7.Q.1

Suppose we want to fit a generalized additive model (with a continuous response) for y against X_1 and X_2. Suppose that we are using a cubic spline with four knots for each variable (so our model can be expressed as a linear regression after the right basis expansion).

Suppose that we fit our model by the following three steps:

1) First fit our cubic spline model for y against X_1, obtaining the fit \hat f_1(x) and residuals r_i = y_i - \hat f_1(X_{i,1}).

2) Then, fit a cubic spline model for r against X_2 to obtain \hat f_2(x).

3) Finally construct fitted values \hat y_i = \hat f_1(X_{i,1}) + \hat f_2(X_{i,2}).

Will we get the same fitted values as we would if we fit the additive model for y against X_1 and X_2 jointly?

- yes, no matter what
- only if X_1 and X_2 are uncorrelated
- **not necessarily, even if X_1 and X_2 are uncorrelated.**