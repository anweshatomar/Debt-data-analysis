# Mortgage and Debt Data Exploration
Analyzing debt data using machine learning models.


## BREIF DESCRIPTION: 


Analyzed mortgage and debt data to determine how an individual is affected by debt given their classification and uncover any disparities between groups.

Performed data pre-processing to eliminate outliers and replaced missing values.

Conducted feature selection to find the most important features.

Further analysis was done using the KNN, SVM and Logistic Regression, the three methods were then ensembled.


## TOP FINDINGS:


- In both cases of debt and rent as target variables, SVM Classifier is our most accurate model in
this dataset along with logistic regression, ensembling and KNN Classifier all resulting in above
75% accuracy.
- Most of the regressions are lower in accuracy since the model is required to predict a number from the min to max of a target, increasing the amount of error exponentially, the lower regression accuracy
is due to the fact that the values of features are in most cases summary or proportion statistics.
- In the case of debt prediction, age seems to be positively
correlated to the percentage of debt while higher household income, home equity and education seem to be
negatively correlated to debt. 
- In the case of average rent, family income and education are the most correlated for predicting higher rent for these subgroups, while household income seems to be inversely significant.
