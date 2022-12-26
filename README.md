# Credit-Default-Prediction
![image](https://user-images.githubusercontent.com/109312561/205520245-0988e661-d4ae-42ee-bed0-36587bd6f7bd.png)

##Introduction

Whether in a restaurant or purchasing concert tickets, contemporary life relies on the ease of a credit card to make daily expenditures. It relieves us from having to carry significant quantities of cash and can even advance a whole purchase that may be paid off over time. How do credit card companies know we'll pay back what we charge? This is a complicated topic with several known solutions—and even more possible enhancements, which will be investigated in this competition.

Credit default prediction is critical to risk management in the consumer lending industry. Credit default prediction enables lenders to optimize loan decisions, resulting in a better client experience and more profitable business.

Here is the link [https://www.kaggle.com/datasets/munumbutt/amexfeather] to dataset we used

## Description

In this project, we aimed to improve credit default prediction in the consumer lending industry using machine learning techniques. Credit default prediction is a critical aspect of risk management for lenders, as it allows them to make informed decisions about whether to extend credit to a particular individual or business. Accurate credit default prediction can result in a better client experience and more profitable business for lenders, while inaccurate predictions can have negative consequences for both lenders and consumers.

To tackle this problem, we obtained a dataset of credit card transactions and customer information from a major credit card company. This dataset included a range of standard features such as income, employment status, and credit history, as well as more subtle features like spending patterns and payment history. We used this dataset to train and evaluate machine learning models that were designed to predict credit default.

We experimented with various algorithms and techniques, including decision trees, logistic regression, and neural networks, and used cross-validation and hyperparameter optimization to select the most effective model. We also applied feature engineering and feature selection techniques to identify the most relevant and predictive features for credit default prediction.

Our final model achieved a Gini score of 0.79 on the test set, demonstrating its ability to accurately predict credit default with a high level of confidence. This score was significantly higher than the benchmark models that we tested, and indicated that our model was more effective at predicting credit default.

-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Steps Followed:
1. We extracted a tiny fraction of the original data from the [kaggle site]([url](https://www.kaggle.com/competitions/amex-default-prediction/data)).
2. Replace all the null values with the KNN imputer, because the data had nearly 22% of the variables with more than 70% nulls, and because the data was financial, we did not want to replace it with any 0 because 0 had a singinficance in our data, and replacing it with mean would not be an ideal case because 14% of the variables had 99% null values present.
3. Executed EDA using the Autoviz library and manual approaches
4. Used Feature Engineering on the datasets
5. Since it is a classification problem, we decided to use Tree algorithms for prediction. On a completely new test data set, we predicted the target variable.
6. Classification and Confusion Matrix were used to evaluate the model.
