# Car Price Prediction Based on Consumer Traits
## STAT 301 Project Group 22 Project Proposal
### By Janice Chan, Elias Khan, Davis Li, Daniel Yuan

## Introduction
One of our team members, Davis, is studying business and works at a Honda retailer selling cars. We found this car dataset from Kaggle that stood out to us because it is directly correlated to what we’re interested in. As a salesman, it is important to gauge how much a client is willing to pay for a car to make the best suggestions. This dataset helps us answer that question by providing input variables (demographics/attributes of a buyer) to predict the response variable (the price they paid for the car).

## Question:
The key question we inquire is: “what attributes of a buyer can best predict how much a buyer is willing to pay for a car?”. As our project is based on prediction, we want to predict: “based on attributes of a buyer/consumer, how much would they be willing to pay for a car?”.

## Dataset:
“Car Sales Price Prediction” from Kaggle: https://www.kaggle.com/datasets/yashpaloswal/ann-car-sales-price-prediction (Yashpal, n.d.), consisting of 500 observations.

The input variables are customer name, customer email, country, gender, age, annual salary, credit card debt, and net worth.

The response variable is the amount paid for a car by the buyer.

A drawback to our dataset is that it does not indicate the currency type for the variables regarding currency and whether they differ, which may conflict as there are various countries. However, we chose to generalize that they are all the same currency as listed together in one variable for convenience and decided to filter out countries in response to possible confusion.

## Relevant Research
From previous studies, we know that the attributes of buyers affect how much they spend on a car. A scientific study by Chandra et al. (2013) describes that older buyers spend more on a car; a trend particularly illustrated in women, indicating that the gender and age of the buyer affect how much they pay for the car. Another study found that income influenced the choice of car price; not gender or age (Rimple et al., 2015).

However, the study by Chandra et al. (2013) does not consider consumers' income/wealth, and the study by Rimple et al. (2015) was limited to a small sample size of 164 respondents in India. Thus, our research will expand on previous studies to gain a better understanding of how customer's traits may affect how much a buyer would spend on a car with a larger and more diverse dataset; providing a better model for prediction and knowledge of the relationship between buyers and their car purchases.
