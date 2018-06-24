# Stander-Val-Pred
Stander Value Prediction
According to Epsilon research, 80% of customers are more likely to do business with you if you provide personalized service. Banking is no exception.

The digitalization of everyday lives means that customers expect services to be delivered in a personalized and timely manner… and often before they´ve even realized they need the service. In their 3rd Kaggle competition, Santander Group aims to go a step beyond recognizing that there is a need to provide a customer a financial service and intends to determine the amount or value of the customer's transaction. This means anticipating customer needs in a more concrete, but also simple and personal way. With so many choices for financial services, this need is greater now than ever before.

In this competition, Santander Group is asking Kagglers to help them identify the value of transactions for each potential customer. This is a first step that Santander needs to nail in order to personalize their services at scale.

The evaluation metric for this competition is Root Mean Squared Logarithmic Error.

The RMSLE is calculated as

ϵ=1n∑i=1n(log(pi+1)−log(ai+1))2−−−−−−−−−−−−−−−−−−−−−−−−−−√
Where:

ϵ is the RMSLE value (score)
n is the total number of observations in the (public/private) data set,
pi is your prediction of target, and
ai is the actual target for i. 
log(x) is the natural logarithm of x

https://www.kaggle.com/c/santander-value-prediction-challenge#evaluation
