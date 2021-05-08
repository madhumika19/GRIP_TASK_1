# Prediction using Supervised Machine Learning

#Objective
To predict the percentage of a student based on the number of study hours using simple linear regression.

#Linear Regression
Linear regression attempts to model the relationship between two variables by fitting a linear equation to observed data. One variable is considered to be an explanatory variable, and the other is considered to be a dependent variable.

Before attempting to fit a linear model to observed data, a modeler should first determine whether or not there is a relationship between the variables of interest. This does not necessarily imply that one variable causes the other (for example, higher SAT scores do not cause higher college grades), but that there is some significant association between the two variables. If there appears to be no association between the proposed explanatory and dependent variables, then fitting a linear regression model to the data probably will not provide a useful model.

A linear regression line has an equation of the form `Y = a + bX`, where `X` is the explanatory variable and `Y` is the dependent variable. The slope of the line is `b`, and `a` is the intercept (the value of y when x = 0).

#Simple Linear Regression
Simple linear regression is used to estimate the relationship between two quantitative variables. You can use simple linear regression when you want to know:
1) How strong the relationship is between two variables (e.g. the relationship between rainfall and soil erosion).
2) The value of the dependent variable at a certain value of the independent variable (e.g. the amount of soil erosion at a certain level of rainfall)

Assumptions of simple linear regression
Simple linear regression is a parametric test, meaning that it makes certain assumptions about the data. These assumptions are:

1) **Homogeneity of variance (homoscedasticity):** the size of the error in our prediction doesn’t change significantly across the values of the independent variable.
2) **Independence of observations:** the observations in the dataset were collected using statistically valid sampling methods, and there are no hidden relationships among observations.
3) **Normality:** The data follows a normal distribution.
4) **The relationship between the independent and dependent variable is linear:** the line of best fit through the data points is a straight line (rather than a curve or some sort of grouping factor).

If your data do not meet the assumptions of homoscedasticity or normality, you may be able to use a nonparametric test instead, such as the Spearman rank test.

#Library used
`pandas` `matplotlib.pyplot` `numpy` `statsmodel.api` `sklearn.linear_model` `sklearn.model_selection`

#Dataset used
https://raw.githubusercontent.com/AdiPersonalWorks/Random/master/student_scores%20-%20student_scores.csv

#References
1) http://www.stat.yale.edu/Courses/1997-98/101/linreg.htm
2) https://www.scribbr.com/statistics/simple-linear-regression/
