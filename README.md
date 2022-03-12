# Healthcare-Analytics
This project focuses on applying clustering and classification techniques to determine if there are interesting groupings of counties with similar health outcomes 
and behaviors, and develop a predictive model to see which factors influence health outcomes.  Individuals and governments can use such a model to improve public health outcomes. 

## Data Scource:
https://www.countyhealthrankings.org/

## Data download: 
https://www.countyhealthrankings.org/sites/default/files/media/document/analytic_data2021.csv 

## Variables Detail:
https://www.countyhealthrankings.org/sites/default/files/media/document/2021%20Analytic%20Documentation.pdf

### Tasks performed
1) Exploratory data analysis and subsequent data preparation 
2) Conducted clustering using K-means to find noteworthy groupings of counties that have similar health outcomes and behaviors
3) Built predictive models (Linear Regression & Random Forest Regressor) to find most important factors in predicting premature death. Premature death is defined as the number of years of potential life lost before age 75 per 100,000 population. 
4) Suggestions for improving public health condition

### Insights achieved from data analytics
1. States with a small number of counties show relatively better public health condition, while for large states (a large number of counties), the proportion of counties that shows positive health condition doesn't exceed 1/4. The department of health should pay attention to large states to see whether there is an uneven distribution of resources and insufficient recourses. 
2. Injury deaths, Adult smoking, Excessive Drinking, Teen births, Children in single-parent households, and Children in poverty are important factors to decide the potential life loss years before 75 years old. To improve the public health condition, policies like controlling excessive smoking and drinking, providing special care to children in poverty and single-parent family could be proposed. 
