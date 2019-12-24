# PUBG-Finish-Placement-Prediction
Python code for Kaggle competition

This code is for the PUBG Finish Placement Prediction on Kaggle.
It uses two large data sets train_V2 and test_V2. 
They were too large to add the Github. 
They can be downloaded at https://www.kaggle.com/c/pubg-finish-placement-prediction/data

CODE:

The code starts off with some EDA (Exploratory Data Analysis). I looked at what the data set contained and how large it was.
I then visualized some of the statistics in an attempt to better understand the data and see any possible correlations between the statistics...
and the desired predicted statistic.

The data had to be modified for training/testing. I had to do label encoding on the matchType column in order to change it from an object.
The random forest model does not use object types.
I then had to split the data sets.

Once these were done, I trained the random forest model and then tested it using the test set.
The accuracy of the model was .9678
