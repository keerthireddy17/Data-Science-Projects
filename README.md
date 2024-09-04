<h1 style="font-weight: bold; text-decoration: underline;">Housing Price Prediction</h1>

<strong>Background</strong>:

California’s housing market plays a pivotal role for residents, investors, and policymakers. The market’s complexity, driven by economic trends, population growth, and urban development, necessitates a data-driven approach to make informed decisions regarding property investment and policy-making.

<strong>Objective</strong>:

Enhance Data Quality: Improve preprocessing methods to address missing values, transform categorical variables, and apply feature engineering techniques.

Develop Predictive Model: Create a robust regression model to predict median home prices based on location, housing attributes, economic indicators, and demographics.

Evaluate Performance: Use statistical metrics and visualizations to assess the model’s accuracy and compare its performance against alternative models.

<strong>Methods</strong>:

Linear Regression: Utilized for its effectiveness in predicting continuous variables, assuming a linear relationship between features and house prices.

Log Transformation: Applied to stabilize variance and reduce skewness, enhancing model performance.

Variance Inflation Factor (VIF): Used to detect and address multicollinearity among predictor variables.

<strong>Results</strong>:

Median Income: Moderate positive correlation (0.69) with housing prices, indicating higher incomes lead to more expensive homes.

Housing Characteristics: Weak positive correlations with variables such as median age (0.1) and total rooms (0.13), suggesting newer or larger homes may have higher prices.

Location: Weak negative correlations with latitude (-0.14) and longitude (-0.05), implying slight price decreases in certain areas.

Population Density: Weak negative correlation (-0.03), with higher densities potentially correlating with slightly lower home prices.

The regression model demonstrated strong performance with a high R-squared value, significant coefficients, and minimal prediction errors. 
These insights emphasize the importance of considering socioeconomic and geographic factors in housing market analysis, aiding stakeholders in making informed decisions.
