# Multiple Linear Regression
## Linearity 
Each predictor variable X_i is linearly related to the outcome variable Y. Plotting scatter plots of each X variable against the y-variable one form us which variables likely have a linear relationship with Y.\
🧰 Q-Q plot, pairplot

## Independent Observations
each observation in the dataset is independent. We can only examine this assumption by checking the data collection process. 

## Normality 
The residuals are normally distributed\
🧰 Q-Q plot, Histogram of resids

## Homoscedasticity
The variation of the residuals errors is constant or similar across the model.\
🧰 Plot of fitted values vs resid

## No multicollinearity 
No two independent variables, X_i and X_j can be highly correlated with each other. This means that X_i and X_j cannot be linearly related to each other.\
🧰 scatterplot, pairplot, VIF


> [!NOTE]
> Residuals are the difference between the predicted and observed values. You can calculate residuals after you build a regression model by subtracting the predicted values from the observed values.
> Errors are the natural noise assumed to be in the model.

# Model Interpretation
## OLS 
R squared - The R squared is 0.85, indicating that your model explains about 85% of the variance in body mass.\
Coefficient - every 1 xx increase in CoE of Y param output will increase by CoE value.\
P Value - small so the CoE is statistically significant.

# Model Evaluation
## Overfitting
R squred can get more complicated if more independed vars are added to the equation. Whenever you add another independent variable to a multiple regression model, R squared increases without fail. But not all variables added to a model equally contribute to understanding changes and why this is a problem because the high R squared can be misleading if we're just trying to get a higher squared without considering what each variable contributes. The model becomes very specific to the data it was built on therefore the model is no longer applicable to a larger population. This is called **over-fitting**.\
🔻 No longer applies to the population. Only applies to the model data.\
❓ How to resolve\
Hold out sampling - set aside a part of the data we already had but did not use to fit the model by using a holdout sample\
Adjusted R squared - penalizes unnecessary explanatory variables\

## Bias versus variance
A model that underfits the sample data is described as having a high bias whereas a model that does not perform well on new data is described as having high variance
