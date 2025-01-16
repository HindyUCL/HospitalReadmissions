# BENG0095


1) To process the Train and Test datasets, you need to run: The data_[...].ipynb files. There are three different types of datasets you can generate. 

- df_train_test_.ipynb contains the most basic version of the train and test datasets...

- df_train_test_temp.ipynb contains temporal information (number_previous_readmissions) and a single row for each patient. 
The value of the different parameters for this row come from averaging continuous values and taking the mode of the binary values (hot-one eoncoded), for each patient. On this dataset, Chi-squared feature selection and PCA are applied with thresholds of 99%. 

- df_train_test_seq.ipynb ...

2) To test the data on state-of-the-art Machine Learning models you can run models.ipynb. There are both classical models such as Logistic Regression, Random Forest, XGBoost, and more sophisticated techniques such as LightGBM, etc. 

3) 

