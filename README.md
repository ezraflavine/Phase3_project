## Phase3_project - SyriaTel_Customer_Churn


![image_hs](https://github.com/ezraflavine/Phase3_project/blob/main/image_hs.jpg)



## Overview
With me is the data from the Syrian Telecommunication Network 'SyrianTel_Customer_Churn.csv' that aims to predict whether a customer will ("soon") stop doing business with SyriaTel, a telecommunications company. The people in telecom business need to understand the amount of money lost in the event of customers leaving telecomunication networks after sometime. Since this translates to losing money in business, the interested parties need to be aware of the patterns and whether they can be predictable. 

## DATA LOADING CLEANING AND EDA

The data I have used is already clean and ready to use. I only had to check for outliers, missing values, also checked on the data types.
For classification type of data we use one hot encoder to convert then into binary but again I did that to the important features that went into the models to predict the customer behaviour in relation to the business problem at hand.
Some of the exploratory data analysis that I came up with are as follows;

Data Visualization

![image1.png](https://github.com/ezraflavine/Phase3_project/blob/main/image1.png)

![image2.png](https://github.com/ezraflavine/Phase3_project/blob/main/image2.png)

![image3.png](https://github.com/ezraflavine/Phase3_project/blob/main/image3.png)

![image7.png](https://github.com/ezraflavine/Phase3_project/blob/main/image7.png)

## DATA MODELING

In data modeling I picked 3 models to work with and choose one that work perform better than the other. These models include;

1) Logistic Regression Model
2) Decision Trees Model
3) K-Nearest Neighbors Model

Logistic Regression Model

![Logit_reg.png](https://github.com/ezraflavine/Phase3_project/blob/main/Logit_reg.png)

The logistic regression model's performance, as indicated by these metrics, suggests that it can predict customer churn to some extent. However, there is room for improvement, particularly in terms of increasing recall (capturing more true churn cases) and improving the F1 score. 
After going through all the models. I discovered Decison Trees model to be having one of the best estimates that closely looked at the business problem and solved it in a way that would answer the problem of customers churning or not.
From the information provided the business can comfortably use the metrics to estimate the amount of business they lose every time customers exit their business and the rate at which they exit would help in approximating the losses at a particular time

## RECOMMENDATIONS

![image9.png](https://github.com/ezraflavine/Phase3_project/blob/main/image9.png)

1. Lower the total day charge of phone calls of the customers.
2. Provide stable network and services to reduce the number of customer service calls that the customers make, because the more calls they make to the customer service the more likely they will leave the network.
3. Check on the total international minutes that customers get, if it is low they will churn.
4. The company should improve on the total day minutes they offer their customers, there is alaways a way to find the balance in between so that as the company wins the customer also enjoys.

## CONCLUSION

In conclusion interested parties should work on the top ten important features that may make customers to churn from their telecommunication companies or not. By working on them means that they should ensure that the features are moderated in favour of customers to persuade them to stay.

When the customers stay it saves the company money of having to acquire new customers since as established it is cheaper to maintain existing clients than acquiring new ones.
