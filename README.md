# Credit-Default-Prediction
![image](https://user-images.githubusercontent.com/109312561/205520245-0988e661-d4ae-42ee-bed0-36587bd6f7bd.png)

Whether in a restaurant or purchasing concert tickets, contemporary life relies on the ease of a credit card to make daily expenditures. It relieves us from having to carry significant quantities of cash and can even advance a whole purchase that may be paid off over time. How do credit card companies know we'll pay back what we charge? This is a complicated topic with several known solutions—and even more possible enhancements, which will be investigated in this competition.

Credit default prediction is critical to risk management in the consumer lending industry. Credit default prediction enables lenders to optimize loan decisions, resulting in a better client experience and more profitable business.


-----------------------------------------------------------------------------------------------------------------------------------------------------------
## Steps Followed:
1. We extracted a tiny fraction of the original data from the [kaggle site]([url](https://www.kaggle.com/competitions/amex-default-prediction/data)).
2. Replace all the null values with the KNN imputer, because the data had nearly 22% of the variables with more than 70% nulls, and because the data was financial, we did not want to replace it with any 0 because 0 had a singinficance in our data, and replacing it with mean would not be an ideal case because 14% of the variables had 99% null values present.
3. Executed EDA using the Autoviz library and manual approaches
4. Used Feature Engineering on the datasets
5. Since it is a classification problem, we decided to use Tree algorithms for prediction. On a completely new test data set, we predicted the target variable.
6. Classification and Confusion Matrix were used to evaluate the model.
