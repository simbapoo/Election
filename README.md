# Election
in Visualisation part
1st plot:
Question: what is the relationship between race and choice of candidate?
This plot shows the quantity of counties that candidate won and race of majority in the county.
We can see that Obama won almost all counties where the majority is black. Obviously black people in the USA supported Obama.
 
 2nd plot:
Question: What is the difference in support of each candidate between people with different age categories?
 This plot shows the quantity of counties that candidates won and in age categories below 35 and from 35 to 65.
The support of the candidate is not depending on the age because the ratio is almost the same.
3rd plot:
Question: What is the difference between counties with average income less than average income in the USA and counties with average income more than average in the USA?
 The plot shows the quantity of counties that each candidate won in counties with average income more than average income in the USA(1) and in counties with average income less than average income in the USA(2).

 We can see that Clinton has a higher win rate in counties with average income less than average income in the USA.
4th plot:
Question: how Obama’s margin changed by Regions?
Obama won much more counties in the West. Clinton won a little bit more counties in the Northeast. Midwest and South was equally supporting both candidates.

Task: Create Regression model to predict winning spread of Obama over Clinton Models: we have 4 models for regression:
1) All demographic parameters + Land and Farm area
2) All race and nationality parameters like ‘Black’, ‘White’
3) All parameters about welfare and education and of citizens 4) All parameters about social security
We used an R-squared score to determine which model is the best from this 4. We got a 0.56 score for the first model, 0.21 for the second, 0.19 for the third and 0.12 for the last one. Also mean absolute error, mean squared error and root mean square error for the first model has the least value.
  
  This is a scatterplot of prediction from a regression model. It’s not perfect because our score is only 0.56

We decided to use PCA to decrease the number of features without any loss, so we compressed ‘Asian’, ‘White’, ‘AmericanIndian’, ‘Hispanic’,’Hawiian’ into 1 feature. We didn’t use ‘Black’ because ‘Black’ are important for the prediction because they strongly supported Obama. We predicted again with this new feature and in result got a raise in the score of prediction. From 0.56 to 0.57.
4) Clinton got a good win rate in counties with income less than average in the USA, maybe she could focus on less proggressive countries. She almost won in Iowa, Missouri and Alabama, she must have focus on this 3.
  
