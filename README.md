# Credit Risk Modeling

How do financial firms make a decision on applications for credit cards or loans? In this project I will explore how to apply machine learning techniques to reduce risk and ensure profitability. I will use data sets that emulate real credit applications while focusing on business value.

The EDA notebook contains the details regarding exploration of the data as well as cleaning it. There is a separate notebook for each model.

For this project I trained and tuned the following models:

- Logistic Regression Model
- XGBoost
- Neural Network

### Results:

<b>Logistic Regression</b>:

Base model: 
Accuracy = 0.819
        
|   	     | Precision 	| Recall	|  F1score   |
|:----------:|:----------------:|:-------------:|:----------:|
|Non-Default |      0.90	|   	0.76    |   	0.82 | 
|Default     |      0.45	|   	0.69    |   	0.55 |

Tuned model:
Accuracy : 0.868
|   	     | Precision 	| Recall	|  F1score   |
|:----------:|:----------------:|:-------------:|:----------:|
|Non-Default |      0.92	|   	0.87    |   	0.89 | 
|Default     |      0.61	|   	0.73    |   	0.67 |

<b>XGBoost</b>


<b>Neural Network</b>

