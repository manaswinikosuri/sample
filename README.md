# sample
# thyroid disease detection 
# to develop a web based platform for thyroid disease detection, that accepts user input for test results and symptoms, predicts type of thyroid : no thyroid, hypperthyroid, primary hypothyroid, secondary hypothyroid or compensated hypothyroid.

# the datasets were obtained from Kaggle and Uci repository. hypothyroidd.csv and thyroidDFF.csv were combined using jupyter notebook. the new csv file is store in newDF.csv

# The AI model was created using XGBoost alogorithm. The following kaggle notebook was used as refernce to work on dataset : https://www.kaggle.com/code/emmanuelfwerr/xgboost-multi-class-classification/notebook

# the combined dataset was modified and used to train and test the split data. This was done in combined.ipynb using jupyter notebook. 

# the resulting accuracy using XGBoost algorithm was found to be 0.97. This model was stored in a pickle file using joblib.dump.

# the flask file is used to link all the webpages to the app and display the prediction results.
