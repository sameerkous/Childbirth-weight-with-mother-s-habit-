# Childbirth weight with mother's habit

Low birth weight not necessarily happen because of smoking habit, it could be because of other habits and health condition of mother. With the help of this study, we will see the trend and try to predict if the baby will be low birth weight depending on different dependent variables.  The purpose of this course project is to predict if the baby is going to be underweight or not.

For the project I am planning to investigate the effect of smoking, along with other variables to the birth weight of the baby. In my analysis, we will be in predicting if the baby will be low birth weight.

By creating this model people will have the ability to see if their baby is going to be underweight because of different factors out of which smoking is one. The doctors and the health care providers will be interested in solving this issue because this model will help predict if the baby is going to be low weight and the mother will take the necessary precautions as necessary.

DataSet for the project:
https://www.openintro.org/data/index.php?data=births14

Methods/Results
Exploratory Data Analysis (EDA) was performed to see what kind of data is available in the dataset. I looked into the count value which shows the missing values and also look at the minimum and maximum value to find the outliers and incorrect data. We can see that there are many missing values for father’s age, visits, weight gained by the mother and the smoking habit. The distribution of the data was studied to find the best method to handle the missing data. Also, I looked into the histogram to see the distribution of the data

Conclusion
I have used many models and compared the accuracy score for those models. The models that were used are logistic regression, KNN model and RandomForestClassifier. The accuracy for RandomForestClassifier was the highest which came out to be 99.5% i.e. the predictions were very high for this model. Confusion matrix and classification report for those models were also observed and we see that the metrics were very good for RandomForestClassifier. 

From different model, RandomForestClassifier has the highest accuracy, and the recommendation will be made to use this model. This model will help in predicting whether the baby will be low weight depending on different features selected. This will help the health care provider to determine if the baby will be in risk because of low birth weight. 

From this project, I learnt how the dataset can be useful to solve the problem in practical life. I also learnt that in data science you come up with one idea and start the project, but you might not be successful in completing the project because the project with be modified to something else when we continue with the project. This happened in my project when I was trying to figure out if smoking causes the low birth weight but when I continued working on project, I realized it’s better to include other factors involved in pregnancy that affects the weight of the baby rather than just looking at smoking. 
