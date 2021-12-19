
![image](https://raw.githubusercontent.com/TomGermeau/BlancPain/main/data/Blancpain_logo.png)


## Team members
Our team consists of Tom Germeau, Lucas David and Martina Kofler.

## Brief description of the project
The objective of the project was the built a model that can predict the difficulty levels of given french sentences for english speakers.

## Approach
For reaching this objective we first loaded  and installed the necessary packages. Then we loaded the train data set from our Github repository in the notebook, the same we did also for the unlabelled dataset on which we should make predictions to load in the leaderboard.

To know what the minimal accurancy is that our models should have we first calculated the baseline.
Then we trained a simple logistic regression model, KNN classification model, Decison Tree classifier and Random Forest Classifier using a Tfidf vectoriser without makeing any data cleaning.

By trying to improve our models we also used tokanization, lemmatization and the removal of stopwords, punctuations and numbers. 
For searching the best parameters for our models we used GridSearch.

The remove of puntuation and numbers, limatization and the parameter optimization helped us to improve the accurancy of our model.

This are our best results

|| Logistic Regression| Random Forest | knn| Decision Tree | Any other technique|
-------------| -------------------- | ------------- |---------------|--------|------|-----|
|Precision|0.4733|0.4100|0.4007|0.3071|0.4921|
|Recall|0.4756|0.4166|0.3183|0.3056|0.4921|
|F1-score|0.4704|0.4018|0.3022|0.3026|0.4878|
|Accurancy|0.740|0.4146|0.3187|0.3052|0.4917|
