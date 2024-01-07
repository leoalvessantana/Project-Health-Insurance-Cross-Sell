# Health Insurance Cross Sell

This repository contains all steps based on the CRISP-DS process model methodology to create a classification model to help a fictitious insurance company maximize sales of a new product. 


## 1. Business Problem

The insurer currently only offers health insurance to its customers and wants to offer a new product: vehicle insurance.

To understand customers' interest in purchasing this new product, the company carried out a survey of its customer base and recorded each customer's response. However, although more than 350 thousand customers responded to the survey, there are still more than 120 thousand new customers that the company does not know if they are interested or not.

As the company has limited resources to reach the customer base (by call, message, email, etc.), the challenge is to use the available resources to reach the maximum number of customers who will purchase the new product.

Therefore, this project aims to create a classification model that will classify new customers according to their propensity to purchase the new product.


## 2. Data

The data used in this project can be found at [Kaggle](https://www.kaggle.com/datasets/anmolkumar/health-insurance-cross-sell-prediction).

<details><summary>Click here to see the original attibutes table</summary><br>
  
Attribute | Definition
------------ | -------------
|id|Unique ID for the customer|
|Gender | Gender of the customer|
|Age|Age of the customer|
|Driving_License|0: Customer does not have DL, 1: Customer already has DL|
|Region_Code|Unique code for the region of the customer|
|Previously_Insured|1: Customer already has Vehicle Insurance, 0: Customer doesn't have Vehicle Insurance|
|Vehicle_Age|Age of the Vehicle|
|Vehicle_Damage|1: Customer got his/her vehicle damaged in the past. 0: Customer didn't get his/her vehicle damaged in the past|
|Annual_Premium|The amount customer needs to pay as premium in the year|
|PolicySalesChannel|Anonymized Code for the channel of outreaching to the customer ie. Different Agents, Over Mail, Over Phone, In Person, etc.|
|Vintage|Number of Days, Customer has been associated with the company|
|Response|1: Customer is interested, 0: Customer is not interested|
</details>


## 3. Business Assumptions

* Customers that aswered yes (1) in the columns<i>"Response"</i> are highly likely to buy the vehicle insurance.
* Customers that aswered no (0) in the columns<i>"Response"</i> are definitely not a buy.
* The company has resources to make from 20,000 to 40,000 calls.
* Each sell will correspond to a monetary value of 2,000 of the currency in the data (there is no information on the currency)


## 4. Solution Strategy

0. Tools
1. Data Description Analysis
2. Feature Engineering
3. Data Filtering
4. Exploratory Data Analysis
5. Data Preparation
6. Feature Selection
7. Machine Learning Modeling 
8. Hyperparameter Fine Tuning
9. Understand Model Performance
10. Deploy



