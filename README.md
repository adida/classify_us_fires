# classify_us_fires
A machine learning model that can predict what caused a fire.
This is a group project done as part of a 'Applied Competitive Lab in Data Science'
course at the Hebrew University in Jerusalem and was graded 98/100. 

Given [this dataset from Kaggle](https://www.kaggle.com/datasets/rtatman/188-million-us-wildfires), our
task was modeling and predicting the cause of the fire. The metric we were required to
optimize is the mean (non-weighted) ROC AUC score for all classes.


## Files
This project contains 4 files:
* data_analysis.ipynb - This file contains the code we used for the data exploration. It contains graphs 
  and explanations. Using the information in this file we learned about the data and made decisions about feature engineering and about the model we chose to build.

* train_test_pipeline.ipynb - This file contains all the work we did after data exploration like feature 
  engineering, hyper-parameters selection, training and evaluating the model and feature importance analysis. 
  
* final_pipeline.ipynb - This file contains what you need to run in order to test our model. It has a 
  fit function to train it, a score function to evaluate the model, and a predict function to get the model’s predictions.
All these functions expect to get the raw data as a pandas dataframe.
