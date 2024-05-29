# Python-Projects

**Hypothesis Testing:**

Null Hypothesis (𝐻0): The means of all groups are equal.

Alternative Hypothesis (𝐻1): At least one group mean is different.

_Z-Score:_

Hypothesis testing with a z-score is a statistical method used to determine if there is a significant difference between a sample mean and the population mean, assuming the population variance is known. It involves calculating the z-score, which measures the number of standard deviations a data point is from the population mean. If the calculated z-score falls beyond the critical value for a chosen significance level (e.g., 0.05), the null hypothesis is rejected, indicating that the observed effect is statistically significant.

_Chi-Square Test:_

A chi-square test evaluates if there is a significant association between categorical variables. It compares the observed frequencies in each category to the frequencies expected under the null hypothesis, which typically states that there is no association between the variables. The test calculates a chi-squared statistic and a corresponding p-value to decide whether to reject the null hypothesis. Common applications include tests of independence in contingency tables and goodness-of-fit tests.

_ANOVA Test:_

ANOVA (Analysis of Variance) is a statistical test used to determine if there are significant differences between the means of three or more groups. It compares the variance within groups to the variance between groups to assess whether the group means are significantly different from each other.



**Logistic Regression:**

Logistic Regression is a statistical method used for analyzing datasets in which there are one or more independent variables that determine an outcome. The outcome is measured with a dichotomous variable (in which there are only two possible outcomes). It is widely used to model the probability of a binary response based on one or more predictor variables.

_Explanatory Logistic Regression Model:_
Objective: To identify factors that influence a binary outcome.

_Predictive Logistic Regression Model:_
Objective: To predict a binary outcome.


**Linear Regression Model:**

Linear Regression is a statistical method used to model the relationship between a dependent variable (also called the target or outcome variable) and one or more independent variables (also known as predictors or features). The goal of linear regression is to find the best-fitting linear equation that can predict the dependent variable based on the independent variables.

_Explanatory Linear Regression Model:_
Objective: An explanatory model is used to offer an explanation of a past event. Assess the relationship between the outcome variable and a factor(indepedent variable).

_Predictive Linear Regression Model:_
Objective: A predictive model is used when we want to predict the value of the outcome variable for a future time.

Thus, we note that explanatory models are backward looking (explaining the past) and the predictive models are forward looking (predicting the future).

**K-Nearest Neighbors (KNN):**

K-Nearest Neighbors (KNN) is a simple, instance-based learning algorithm that is used for classification and regression tasks. In KNN, the target value of a data point is determined by the majority class (for classification) or the average (for regression) of its k-nearest neighbors in the feature space. 

The key steps are:

1. Choosing the number of neighbors (k).
2. Calculating the distance between the data points.
3. Sorting the data points based on distance.
4. Voting for the majority class or averaging the values.
