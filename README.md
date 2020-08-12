# Graphical Granger Methods

Reviewing granger causality and methods to extract structure. 

### Outline

* Overview

This notion is based on the idea that a cause should be helpful in predicting the future effects, beyond what can be predicted solely based on their own past values.

x is said to “Granger cause” another time series y, if and only if regressing for y in terms of both past values of y and x is statistically significantly more accurate than doing so with past values of y only.

Granger Causality Test
* Y = A * y_lag
* Y = A * y_lag + B * x_lag

Then get perform F-test to obtain p-value.

* Data Generation and Evaluation
* Methods
    * Exhaustive Seardh
    * LASSO
    * SIN
    * VAR
    * Non-Linear Methods
* Demos
