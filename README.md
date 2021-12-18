
![image](https://raw.githubusercontent.com/TomGermeau/BlancPain/main/data/Blancpain_logo.png)


## Team members
Our team consists of Tom Germeau, Lucas David and Martina Kofler.

## Brief description of the project
The objective of the project was the built a model that can predict the difficulty levels of given french sentences for english speakers.

## Approach
For reaching this objective we first loaded the necessary modules and installed the necessary packaeges. Then we loaded the train data set from our Github repository in the notebook, the same we did also for the unlabelled dataset on which we should make predictions to load in the leaderboard.

To know what the minimal accurancy is that our models should have we first calculated the baseline.
Then we trained a simple logistic regression model, KNN classification model, Decison Tree classifier and Random Forest Classifier using a Tfidf vectoriser without makeing any data cleaning.

By trying to improve our models we also used tokanization, lemmatization and the removal of stopwords and punctuations. 
For searching the best parameters for our models we used GridSearch.

The tokanization, limatization and the parameter optimization helped us to improve the accurancy of our model.
