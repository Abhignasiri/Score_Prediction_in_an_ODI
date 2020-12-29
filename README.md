# Score_Prediction_in_an_ODI
Prediction of First Innings Score in an ODI

• Second Major Project of Verzeo Data Science Internship. <br/>
• Took data of the year 2006 for experimenting. <br/>
• Did exploratory data analysis on average runs scored by each country. <br/>
• Did dummy encoding to convert categorical columns of the data set to numerical type. <br/>
• Performed Logistic Regression, Decision Tree Regression and Random Forest Regression algorithms by proper feature scaling. <br/>
• Predicted on test data using these models with evaluation. <br/>


## Instructions

1. Load the dataset from the csv file. <br/>
2. Use “groupby” operation, to find the average number of runs, scored by each country, and represent it on a bar graph. <br/>
3. Handle Missing values: <br/>
  a. If there are null values in continuous numerical column, replace the null values by the mean of that column <br/>
  b. If there are null values in ordinal numerical column, replace the null values by the mode of that column <br/>
  c. If there are null values in categorical column, replace the null values by the mode of that column <br/>
  d. If more than 50% the values in a column are null, then drop that entire column <br/>
4. Remove the columns, that you think, do not contribute to the total score, in the first innings. <br/>
5. Convert the categorical columns (if any), to numeric, using one hot encoding/ dummy encoding. <br/>
6. Pick “total” column, as the target variable <br/>
7. Select the relevant features. <br/>
8. Perform train-test-split <br/>
9. Perform Feature scaling <br/>
10. Use <br/>
  a. Use Linear Regression <br/>
  b. Use Decision Tree Regression <br/>
  c. Use Random Forest Regression <br/>
11. Evaluate the model <br/>
12. Apply prediction <br/>
