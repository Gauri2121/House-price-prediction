house price prediction 
The real estate sector is an important industry with many stakeholders ranging
from regulatory bodies to private companies and investors. Among these stakeholders, there is a high demand for a better understanding of the industry operational
mechanism and driving factors.
Today there is a large amount of data available on relevant statistics as well as
on additional contextual factors, and it is natural to try to make use of these in
order to improve our understanding of the industry. Notably, this has been done in
In housing prices 
In some cases, non-traditional variables have proved to be useful predictors of
real estate trends. For example,  it is observed that Seattle apartments close
to specialty food stores such as Whole Foods experienced a higher increase in value
than average.
This project can be considered as a further step towards more evidence-based
decision making for the benefit of these stakeholders. The project focused on assessment value for residential properties in Calgary between 2017-2020 based on data
from [1]. The aim of our project was to build a predictive model for change in house
prices in the year 2021 based on certain time and geography dependent variables.
The main steps in our research were the following.
• Exploratory Data Analysis (EDA).
By conducting explanatory data analysis, we obtain a better understanding
of our data. This yields insights that can be helpful later when building a
model, as well as insights that are independently interesting.
• Feature Selection
In order to avoid overfitting issues, we select 20(according to PCA [12])
variables out of the original 36 by using methods ANOVA , LASSO [14],
elastic net [15], forward feature selection, backward feature selection.
• Modeling
We apply Decision Tree , Random Forest  and Xgboost models for
prediction of the percentage change of the housing prices.
