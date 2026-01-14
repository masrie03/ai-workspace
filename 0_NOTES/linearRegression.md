# Linear Regression

## Definition
Linear regression models the relationship between a dependent variable y
and one or more independent variables X by fitting a linear equation(Straight line).

> Why straight line?
 Because it follows a pattern, it tells you what should happen in places you havent visited yet

## three foundational concerns
1. Signal
Is there anything real to learn?

2. Structure
What is the relationship and who drives it?

3. Trust
When should I believe this output?

## When to Use
- Relationship is approximately linear
- Continuous target variable
- Interpretability is important

## Main concepts
1. Use least-squares to fit a line to the data
2. calculate R^2
3. calculate a p-value for R^2

## Mathematical Form
y = wX + b

> w (weight)

## Key Assumptions
- Linearity
- Independence
- Homoscedasticity
- No multicollinearity

## Common Pitfalls
- Outliers affecting the fit
- Using linear regression for non-linear data
- Multicollinearity between features

## Python Pattern
- sklearn.linear_model.LinearRegression
- train_test_split
- Mean Squared Error

## Related Notebooks
- ../notebooks/01_linear_regression.ipynb  ## tukar kepada loc kau 
