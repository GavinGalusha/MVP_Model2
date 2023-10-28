# MVP_Model2
Data Science Project to determine NBA MVP

In this project I employed a random forest classifier to build a MVP prediction model. 

-To Start, I stringed together 3 different sets of datasets from 2000-2021, which brought together multiple statistics including player stats, team stats, and advanced NBA metrics.

-I then cleaned the data and generated multiple new features as the datasets merged together, with the help of a map to build one big dataframe based on the common columns in the datasets.

-From there, I oversampled to get more occurences to train the classifier on, and used a random grid with 5 fold cross validation in order to determine the best hyperparameters for the classifier.

-After evaluating the model, I saw a 98% accuracy in prediction of MVP, and when testing on 2022 nba all stars, my model was able to predict 8 out of 10 of the top canditates that placed in MVP voting that year.
