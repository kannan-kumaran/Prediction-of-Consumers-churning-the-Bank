# Prediction-of-Consumers-churning-the-Bank
The project aims to: Identify and illustrate the factors/features that contribute to customer attrition. Construct and train a machine learning model to anticipate churns and assist customer care. Reduce customer churn and profit loss by focusing on the causes that may lead to churn.
## Objective
To uncover and visualise the elements that contribute to client churn, exploratory data analysis (EDA) was utilized. This data will be used to construct Machine Learning models that will forecast whether or not a customer would churn.This problem is a typical classification task to estimate whether a bank's customers leave the bank or not. <br/>
## Data Description
The dataset containing 10000 rows and 14 columns was considered. This dataset was obtained from Kaggle.  This dataset contains information about the card holder in a bank and their possibility of churn. The attributes in the dataset are customer_id, credit_score, country, gender, age, tenure, balance, products_number, credit_card, active_member, estimated_salary, and churn.  A value of 1 for churn indicates that the member has exited while 0 indicates the member is still using the bank. 

Below is a tabular representation of the dataset contents:

![alt text](https://github.com/siddhaling/Bank-Churn-Prediction-using-Deep-Learning-And-Machine-Learning-Models/blob/main/1.jpg)

 <br/> Source dataset: https://www.kaggle.com/shivan118/churn-modeling-dataset
## Methodology
The research dwelves into tackling churn in the prevention proces by forecasting the probability of a current customer exiting based on their overall financial records. The methodology is two-folded firstly we create a prediction model and test it and lastly, conduct an analysis of the various attributes of customers that contribute to churn in recent times
![alt text](https://github.com/siddhaling/Bank-Churn-Prediction-using-Deep-Learning-And-Machine-Learning-Models/blob/main/3.jpg)
## Data Pre-processing
There were no missing values in the dataset. In the real-world, data will be available in all sorts of forms. Identifying missing values and data would be an important step in order to handle them and build a successful model. To build a model to predict customer churn, columns such as “RowNumber”, “CustomerID” and “Surname” were irrelevant, so they were excluded from the dataframe. Features such as “NumOfProducts”, “HasCrCard”, “IsActiveMember”, “Tenure” and “Exited” are integers and were changed into categorical type. The dataset was normalized and stored into another dataframe if demanded by the ML algorithm used.
## Models
Four models were compared to check for maximum efficiency based on researching related works. They are,

- Naive Bayes
- Decision Tree
- Random Forest
- Gradient Boosting
## Evaluation Metrics
- Accuracy
- ROC Curve
- Time Taken
- Confusion Matrix
- Classification Report

## Conclusion
Random Forest and Gradient Boosting have performed equally and produced high ROC_AUC score (~87%). But ***Gradient Boosting*** took lesser amount of time compared to time taken by Random Forest. Therefore, we can conclude that Gradient Boosting as the best model. <br/>
