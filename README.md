# Default-Predictors

## About the Data

### April 2005 — September 2005 Taiwanese Consumer Credit Payments

The data set was acquired from a research that focused on predicting the probability of default payments among customers in Taiwan using six data mining methods. Since the actual probability of default was unknown, the research introduced a new method called the "Sorting Smoothing Method" to estimate probability of default.

They then used the estimated probability as the response variable and the predictive probability of default as the independent variable in a simple linear regression. What they found was that an artificial neural network method had the highest coefficient of determination, with a regression intercept close to zero and a regression coefficient close to one. As a result, the artificial neural network method is the one they chose.

## Tools
- Tidyverse
- Quarto

## Conclusion

Based on the data, a higher credit balance and a higher payment made towards the previous month's bill are associated with a lower chance of defaulting on a credit account in the next month.

While delays in payment are significant in predicting default for September, July, and April; August predicts no default in October.

Compared to the expected borrower of Female, University educated, and Single: Male borrowers increased defaulting chances, Married borrowers increased defaulting chances, and graduates that considered themselves "Other" decreased defaulting chances.

### References

Yeh, I-Cheng, and Che-hui Lien. 2009. “The Comparisons of Data Mining Techniques for the Predictive Accuracy of Probability of Default of Credit Card Clients.” Expert Systems with Applications 36 (2): 2473–80. https://doi.org/10.1016/j.eswa.2007.12.020.
