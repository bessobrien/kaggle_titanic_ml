# Kaggle Competition: Titanic - A Machine Learning Disaster  
<br>

### **Objective**:

Use Titanic passenger data to try to predict who will survive and who will die using machine learning.

### **Technologies Used**:
1. Kaggle Notebooks
2. VSCode 1.78.2

### **Languages Used**:
1. Python3
2. Pandas
3. NumPy
4. SKLearn

### **Summary**:

To determine who will survive, we were provided training and test datasets. First step was to use Pandas to convert the training and test data csv files to dataframes.

![to_df](https://github.com/bessobrien/kaggle_titanic_ml/blob/main/Screenshots/to_df.png)

Once I verified that both were converted to dataframes successfully, I did an initial analysis on the training dataframe:

1. Find the rate of women who survived (74.2%):

![f_rate](https://github.com/bessobrien/kaggle_titanic_ml/blob/main/Screenshots/f_rate.png)

2. Find the rate of men who survived (18.89%):

![m_rate](https://github.com/bessobrien/kaggle_titanic_ml/blob/main/Screenshots/m_rate.png)

Once initial preview analysis was done, I utilized a Random Forest model, with 100 layers to train the data to get survival predictions for the list of passengers.

Once submitted, the predictions returned 77.51% accuracy.

![ml_model](https://github.com/bessobrien/kaggle_titanic_ml/blob/main/Screenshots/ml_model.png)

