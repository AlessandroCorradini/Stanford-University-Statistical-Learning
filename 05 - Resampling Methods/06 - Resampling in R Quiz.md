# Resampling in R Quiz

## 5.R.R1

Download the file 5.R.RData and load it into R using load("5.R.RData"). Consider the linear regression model of y on X1 and X2. What is the standard error for ?

**0.02593**

## 5.R.R2

Next, plot the data using matplot(Xy,type="l"). Which of the following do you think is most likely given what you see?

- Our estimate of s.e.(\hat\beta_1) is too high.
- **Our estimate of s.e.(\hat\beta_1) is too low.**
- Our estimate of s.e.(\hat\beta_1) is about right.

## 5.R.R3

Now, use the (standard) bootstrap to estimate . To within 10%, what do you get?

**0.0274**

## 5.R.R4

Finally, use the block bootstrap to estimate s.e.(\hat\beta_1). Use blocks of 100 contiguous observations, and resample ten whole blocks with replacement then paste them together to construct each bootstrap time series. For example, one of your bootstrap resamples could be:

```
new.rows = c(101:200, 401:500, 101:200, 901:1000, 301:400, 1:100, 1:100, 801:900, 201:300, 701:800)

new.Xy = Xy[new.rows, ]
```

To within 10%, what do you get?

**0.2**
