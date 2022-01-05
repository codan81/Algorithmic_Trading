# Algorithmic_Trading

# Overview

This is a Jupyter notebook whose purpose is identify the Creditworthiness of borrowers by the creation of two machine learning models: one unbalanced and balanced with the financial information data provided in a dataset of historical lending activity from a peer-to-peer lending services company.

To predict this supervised binary classification problem. I was provided with a lending_data.csv file which was read by python and converted into a dataframe, with the creation of labels and features datasets. The labels variable (y) contains  "loan_status" column. A value of 0 in the “loan_status” column means that the loan is healthy. A value of 1 means that the loan has a high risk of defaulting., The features variable (X) contains the remaining columns of the dataframe. Then I check the balance of the variable (y) with the help of the value_counts function to check how balanced or unbalanced the variable was then I split the data in training and testing datasets with train_test_split. 




![Algorithmic_trading](images/Decision_tree_plot.png)

in the machine learning process I went through diferent stages as  fitting the model to the data, making predictions, and then evaluating the quality of those predictions using methods like LogisticRegretion to create a logistic regretion model and RandomOverSampler to resample the data. 

![Algorithmic_trading](images/svm_plot.png)

---

## Technologies

This setup assumes you already have conda installed.

This project leverages python 3.7 with the following packages:



---

## Results

* Machine Learning Model 1:
  
  * I found that the model 1 wich include the original data is 95% of accuracy
  
  * With a Precision of 100% on the "0" (healthy loans), and 85% on the "1" (risky loans)
  
  * The Recall scores where for "0" 99% and for "1" was of 91%.



* Machine Learning Model 2:
  
  * The Model 2 wich include the resampled data is 99% of accuracy
  
  * With a Precision of 100% on the "0" (healthy loans), and 84% on the "1" (risky loans)
  
  * The Recall scores where for "0" 99% and for "1" was of 99%.
  
---

## Summary

* The model number 2 with the resampled data seems to be the one that performs better due to the diference in accuracy with 99% vs 95% of the model 1., Even when the precision on the model 2 is lower 1% in "1" but in the recall scores the model 2 was better with 8% higher difference against the moldel 1  

* The performance in the problem to solve was better in model 2 since the improvement was more noticeable on the "1" which is the more important factor to predict to be able to detect risky loans 




---
## Contributors

Israel Fernandez

---
