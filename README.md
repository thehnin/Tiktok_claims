# Multiple Linear Regression
## Linearity 
Each predictor variable X_i is linearly related to the outcome variable Y. Plotting scatter plots of each X variable against the y-variable one form us which variables likely have a linear relationship with Y.
🧰 Q-Q plot, pairplot

## Independent Observations
each observation in the dataset is independent. We can only examine this assumption by checking the data collection process. 

## Normality 
The residuals are normally distributed
🧰 Q-Q plot, Histogram of resids

## Homoscedasticity
The variation of the residuals errors is constant or similar across the model.
🧰 Plot of fitted values vs resid

## No multicollinearity 
No two independent variables, X_i and X_j can be highly correlated with each other. This means that X_i and X_j cannot be linearly related to each other. 
🧰 scatterplot, pairplot, VIF


> [!NOTE]
> Residuals are the difference between the predicted and observed values. You can calculate residuals after you build a regression model by subtracting the predicted values from the observed values.
> Errors are the natural noise assumed to be in the model.
