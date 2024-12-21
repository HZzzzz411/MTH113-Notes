# Graphical and Numerical Methods for Summarizing Bivariate Data
## Bivariate Data
- **Bivariate Data**: Data consisting of **pairs of** numerical variables (x, y).
- **Scatter plot**: A graphical representation of bivariate data, showing the relationship between x and y.

## Relationships
- **Form**: Linear, non-linear.
- **Direction**: Positive (as x increases, y increases), Negative (as x increases, y decreases).
- **Strength**: Weak, moderate, strong.

## Correlation
- **Correlation Coefficient (r)**: s a numerical assessment of the **strength of the linear relationship** between x and y for a bivariate data set. $r \in [-1, 1]$
- **Sample Correlation Coefficient**:
  <>
$$ r = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{\sqrt{\sum_{i=1}^{n} (x_i - \bar{x})^2 \sum_{i=1}^{n} (y_i - \bar{y})^2}}$$
- **Properties of r**:
  - Symmetric: \( r(x, y) = r(y, x) \)
  - Not affected by shifting or scaling.
  - Only valid for linear relationships.

## Linear Regression
- **Dependent Variable (y)**: The variable to be predicted.
- **Independent Variable (x)**: The variable used to predict y.
- **Least-Squares Regression Line**: The line that minimizes the sum of squared residuals.
  - Equation: \( \hat{y} = a + bx \)
  - Slope (b): \( b = \frac{\sum_{i=1}^{n} (x_i - \bar{x})(y_i - \bar{y})}{\sum_{i=1}^{n} (x_i - \bar{x})^2} \)
  - Intercept (a): \( a = \bar{y} - b\bar{x} \)

## Goodness-of-Fit
- **Residuals**: The difference between observed and predicted values.
- **Residual Plot**: A plot of residuals against the independent variable.
- **Coefficient of Determination (R²)**: The proportion of variability in y that can be explained by the linear relationship with x.
  - \( R² = r^2 \)
- **Standard Deviation about the Regression Line (se)**: A measure of the typical deviation of the observed values from the regression line.
  \[
  se = \sqrt{\frac{\sum_{i=1}^{n} (y_i - \hat{y}_i)^2}{n - 2}}
  \]

## Steps in Linear Regression Analysis
1. **Summarize the data graphically** by constructing a scatterplot.
2. **Decide if the relationship is approximately linear** based on the scatterplot.
3. **Find the equation of the least-squares line**.
4. **Construct a residual plot** and look for patterns or unusual features.
5. **Compute and interpret se and R²**.
6. **Decide if the least-squares line is useful for making predictions**.
7. **Use the least-squares line to make predictions**.
