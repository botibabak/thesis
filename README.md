# thesis
My thesis about fraud detection on the field of energy consumption
The codes are divided into 4 jupiter notebook:
  - thesis_without_tuning.ipynb contains the modifications I have made on the dataset to improve the results without tuning the algorithms
  - tuning_logisticRegression.ipynb contains the tuning of the Logistic Regression classifier
  - tuning_randomForest.ipynb contains the tuning of the Random Forest classifier
  - tuning_xgboost.ipynb contains the tuning of the XGBoost classifier and the best results visualized by it

datasets folder contains one txt file with a goodle drive link, where all of the datasets used in the codes are there:
  - data.csv is the whole dataset without modifications
  - full_nanWithRandom.csv is the whole dataset, where the NaN values are filled with a random number between the columns min and max value
  - sorted_and_nansAreMean.csv is a dataset without outliers, NaN values are filled with the mean of the columns, contains the whole time interval
  - sorted_and_nansAreMean_from2015.csv is a dataset without outliers, NaN values are filled with the mean of the columns, contains data from 01/01/2015 to the end of the time interval
  - sorted_and_nansAreMean_from2016.csv is a dataset without outliers, NaN values are filled with the mean of the columns, contains data from 01/01/2016 to the end of the time interval
  - sorted_and_nansAreRandomized.csv is a dataset without outliers, NaN values are filled with a random number between the columns min and max value, contains the whole time interval
  - sorted_and_nansAreMeanRandomized_from2015.csv is a dataset without outliers, NaN values are filled with a random number between the columns min and max value, contains data from 01/01/2015 to the end of the time interval
  - sorted_and_nansAreRandomized_from2016.csv is a dataset without outliers, NaN values are filled with a random number between the columns min and max value, contains data from 01/01/2016 to the end of the time interval
  - sorted_without_outliers_rowAvg.csv is a dataset without outliers, NaN values are filled with the row averages, contains the whole time interval
  - sorted_without_outliers_rowAvg_from2015.csv is a dataset without outliers, NaN values are filled with the row averages, contains data from 01/01/2015 to the end of the time interval
  - sorted_without_outliers_rowAvg_from2016.csv is a dataset without outliers, NaN values are filled with the row averages, contains data from 01/01/2016 to the end of the time interval
  - sorted_with_mean_std.csv is a dataset without outliers, NaN values are filled with the mean of the columns, contains the whole time interval, with added row average and std features
  - sorted_without_outliers_rowAvg.csv is a dataset without outliers, NaN values are filled with the row averages, contains the whole time interval, with added row average and std features
