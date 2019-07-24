# Unsupervised Learning in R Quiz

## 10.R.1

Suppose we want to fit a linear regression, but the number of variables is much larger than the number of observations. In some cases, we may improve the fit by reducing the dimension of the features before.

In this problem, we use a data set with n = 300 and p = 200, so we have more observations than variables, but not by much. Load the data x, y, x.test, and y.test from 10.R.RData.

First, concatenate x and x.test using the rbind functions and perform a principal components analysis on the concatenated data frame (use the "scale=TRUE" option). To within 10% relative error, what proportion of the variance is explained by the first five principal components?

**0.3498565**

## 10.R.2

The previous answer suggests that a relatively small number of "latent variables" account for a substantial fraction of the features' variability. We might believe that these latent variables are more important than linear combinations of the features that have low variance.

We can try forgetting about the raw features and using the first five principal components (computed on rbind(x,x.test)) instead as low-dimensional derived features. What is the mean-squared test error if we regress y on the first five principal components, and use the resulting model to predict y.test?

**0.9923**

## 10.R.3

Now, try an OLS linear regression of y on the matrix x. What is the mean squared predition error if we use the fitted model to predict y.test from x.test?

**3.90714**
