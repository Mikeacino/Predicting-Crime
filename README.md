# Predicting-Crime
Research Question:
What are the factors that best predict criminal behavior in a community?

Data Source:
https://archive.ics.uci.edu/dataset/183/communities+and+crime 

Analysis techniques:
Given the continuous nature of the data I will use Linear Regression with Lasso and Ridge regression.

Cleaning the data:
To start, there were non-predictive(as stated by the provider of the data) features that I removed, along with features that had more than 50% of missing values. Beyond that, I had around 100 features remaining, and 1993 rows of data.

Result:


Why this question is important:
Crime is a big issue for many Americans, and while it has been generally trending downward for a while, it is still a very concerning issue. This analysis could help to inform policy makers that crime is generally not a random act, but can be tied to economic and societal aspects. Analysis in this area helps to build a body of work that informs policy as to the ways to effectively decrease crime across America.

Important Note:
One concern with this data is that this analysis could be miscontrued as a proof of causation of features. In my report, I include a brief section where I calculate correlation to the target feautre. It is vital that readers recall that correlation is not causation. Any conclusions in this project are related to predicting the target feature, not determining that any feature in this dataset causes the change in another feature.
