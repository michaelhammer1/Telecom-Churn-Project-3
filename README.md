# Telecom Churn Predictor
![](https://stlpartners.com/wp-content/uploads/2018/02/Telco-economics-churn.jpg)


# Project Overview

## Key Business Problem
It is 6X cheaper for a telecom company to target a customer who may churn than to acquire a new customer. So, we build a classifier to predict customers most likely to churn given information about how much time they speak on the phone, if they contact customer service and if they use voicemail, etc,. This is a binary classification problem.

## Stakeholders

The dataset is from SyriaTel a Syrian telecom company that seemingly did business in the US or that acquired a US based dataset. The predictions coming out of the model will be most useful for US telecom companies including Verizon, AT&T and T-Mobile. Smaller telecom providers including U.S. Cellular, Union Wireless and Thumb Cellular may also find this useful.

Within these businesses, the advertising and client retention teams should be most interested in this predictor. Management should also use this predictor when deciding how to allocate capital between new customer acquisition and customer retention. 

## Data Understanding and Analysis

The goal of this predictor is to build binary classification models and find the most effective one in terms of recall.

## Data Source

[Churn in Telecom Customers](https://www.kaggle.com/datasets/becksddf/churn-in-telecoms-dataset/code)




Description of data:
This data represents 3333 customers over a period of 9 months. Each row represents a unique phone number and account. There are 21 features in the columns including the number of voicemail messages recieved and the total number of minutes the person spoke on the phone.

## Visualizations

![Churn percentage](https://github.com/michaelhammer1/Telecom-Churn-Project-3/blob/main/data/Screenshot%202023-10-06%20at%204.17.16%20PM.png)

#### Feature Correlation to Churn
<img src="https://i.imgur.com/QXZYHDm.png" width=50% height=50%>

#### Dummy Classifier Confusion Matrix
![Dummy Classifier](https://github.com/michaelhammer1/Telecom-Churn-Project-3/blob/main/data/Screenshot%202023-10-06%20at%204.17.23%20PM.png)


#### Decision Tree with Hyperparameter Adjustments Confusion Matrix
![image](https://github.com/michaelhammer1/Telecom-Churn-Project-3/blob/main/data/Screenshot%202023-10-06%20at%204.17.48%20PM.png)

#### Logistic Regression Confusion Matrix
![image](https://github.com/michaelhammer1/Telecom-Churn-Project-3/blob/main/data/Screenshot%202023-10-06%20at%204.17.56%20PM.png)

## Conclusion

The decsion tree classifier model with hyperparameter tuning has the best performance at predicting the churn rate of telecom customers. It has a recall of 0.86

## Further Improvement

To further improve the model it would be good to have more data, and to test more models, including a neural net and random forest on this data. We can also revist feature importance to see if changing the number of features included would improve the model.

To further improve the model it would be good to have more data, and to test more models, including a neural net and random forest on this data. We can also revist feature importance to see if changing the number of features included would improve the model.

