# Credit Risk Modeling

How do financial firms make a decision on applications for credit cards or loans? In this project I will explore how to apply machine learning techniques to reduce risk and ensure profitability. I will use data sets that emulate real credit applications while focusing on business value.


## Understanding Credit Risk

What is credit risk?

- The possibility that someone who has borrowed money will not repay it all
- When someone fails to repay a loan, it is said to be in default
- The likelihood that someone will default on a loan is the probability of default (PD)


Expected loss: the amount a firms loses as a result of loan default. Expected loss is a calculation of 3 primary components:

- Probability of default (PD): likelihood that someone will default on a loan
- Exposure at default (EAD): the amount outstanding at the time of default
- Loss given default (LGD): the ratio of the exposure against any recovery from the loss. For example, if we loan 100 dollars to someone, 100 is our exposure and if we sell that debt for 20 dollars, our loss given default would be 80%. 

The formula for expected loss is:

Expected_Loss = PD * EAD * LGD

I will focus on probability of default. For modeling probability of default we generally have two primary types of data available: 

- Application data: data which is directly tied to the loan application like loan grade, 
- Behavioral data: describes the recipient of the loan,  such as employment length.
