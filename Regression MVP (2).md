# Regression MVP
For my project I am investigating the relationship between season point totals (assists + goals) and player stats for NHL players. My data covers the last four NHL seasons.

Initial exploration of the data revealed that the number of shots taken significantly impacts the total points per season that player will earn. There appears to be a linear, or slight polynomial, relationship between shots taken per seson and total points, as the below graph shows.

![Points_Shots_Taken.png](attachment:Points_Shots_Taken.png)

Additionally, I created a two feature linear regression model with shots taken and a player's average minutes on-ice per game as the features and total points as the target. The results from this model are as follows:
+ R^2 = 0.832
+ Points = .2736(shots taken) + .1275(average minutes on-ice)

For next steps I plan to add additional features into my model after engineering features that I have in my existing dataset, both numeric (e.g. age) and categorical (e.g. position). If time permits, I'd like to pull in new features such as player salary and player nationality. Additionally I plan to compare model performance across different model types (i.e. linear, ridge and LASSO). 


```python

```
