# Econometrics Project: What Variables Impact Attendance

- **Descriptive Analysis:** Perform a univariate analysis
    - histograms, quantile plots, correlation plots, etc.
    - exploratory analysis using Pandas Profiling
    - Estimate density distributions (e.g., Cullen & Frey)
    - Transformations on any non-linearities within variables
    - Comment on any outliers
    - Impute N/A Values

- **Variable Selection:**
    - Use Boruta Algorithm to identify top 2 predictors
    - Use Mallows Cp to identify top 2 predictors 

- **Model Building:** Explore several competing OLS models
    - Evaluate transformations of variables
    - Look at Cook’s distance Plot, Residuals Plot
    - Evaluate the robustness of coefficient estimates by bootstrapping model
    - Use cross-validation to evaluate model’s performance
