# Linear-regression-models-of-GDP-as-a-function-of-population
# linear regression models of GDP as a function of population
![image](https://github.com/Farhanaislam1/Linear-regression-models-of-GDP-as-a-function-of-population/assets/165937850/6654e773-0743-46fc-bdd3-8370d6c56461)

## Hypothesis Revision
From the log-log we can see that all the models fail for nations with less than 100 million
people. The reason for this failure is our faulty assumption that the intercept $b$ is not
zero. This is physically unrealistic as a nation with no people should have no GPP. In
fact, in the log-linear model, a nation with only one person would have no GDP.

![image](https://github.com/Farhanaislam1/Linear-regression-models-of-GDP-as-a-function-of-population/assets/165937850/46db2971-7500-4b4b-95b5-0fdb0cd70606)

![image](https://github.com/Farhanaislam1/Linear-regression-models-of-GDP-as-a-function-of-population/assets/165937850/6a640bcf-111d-4ddd-8bb4-333c474b55cb)

## Summary
All of the models have consistent fits year over year. Regardless of the model, the
estimated coefficient of the slope, fixing the intercept at zero, increases year over year
corresponding to the well documented GDP intensification of society through the spread
of industrialization.
Here, we can see that both the linear and the log-linear models
estimate well for small populations, while the quadratic model is clearly a
poor estimator.
Including the intercept often provides a better fit for a broader range of data as it allows the model to capture the baseline relationship between the variables when all predictors are zero. Excluding the intercept may fit the specific data points better but might not generalize well to new data or different contexts.

