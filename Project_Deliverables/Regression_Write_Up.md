# Investigating Whether There's a Relationship Between Certain Stats and the Number of Goals and Assists an NHL Player Generates

## Abstract
For my project I focused on the NHL. I investigated whether there is a relationship between certain attributes and stats and the number of points (goals + assists) that a player generates. That is, are there certain stats/attributes have more of an impact on the number of points an NHL player generates over the course of a season. I scraped data from HockeyReference.com and iteratively featured engineered my input variables and used a linear regression model to understand which features had the greatest impact on my target.

## Design
I chose hockey as my project domain because it's a sport I love to watch and play recreationally. Identifying the stats/attributes that impact player point production the most could be useful to an NHL coach who wants to maximize point production from his players. More specifically, model results could be used to choose what types of drills and skills to focus on during practice to emphasize the features that have the greatest impact on the model target. 

## Data
Data for this project came from HockeyReference.com. I scraped player statistics for all NHL rostered players over the course of the past two seasons. This included scraping and inputing into my model both categorical and numeric data. Rostered players who had scored zero points or who had played in zero games were eliminated from my dataset. After data cleaning was completed, I ended up with over 1,300 data points. After completing feature engineering my final model incorporated 6 numeric features and 2 categorical features.

## Algorithms
Feature Engineering:
+ Adding and subtracting features to optimize model metrics
+ Using dummy variables to capture categorical data
+ Exploring interactive features, though ultimately not using in final model

Models:
Linear regression and LASSO regression were used to model my data. I used an 80/20 train test split and 5-fold cross validation when to separate the data. Testing was performed only on the 80% of training data while final model testing was performed on my 20% holdout set.

Final linear regression 5-fold CV score:
+ R^2 = .596

Hold-Out test score:
+ R^2 = .421

## Tools
+ Beautiful Soup for web scraping
+ Pandas for data cleaning/processing
+ Scikit-learn for modeling
+ Seaborn for visualization

## Communication
A brief slide deck was prepared to communicate my findings of which player stats/attributes tend to have the largest impact on an NHL player generating points (goals + assists).


```python

```
