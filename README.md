# BankCustomersChurnPred
 
![bank_costumer_churn_prediction](Results/bank_costumer_churn_prediction.png)

### Author: Emmanuel Edouard Moutoussamy (https://tinyurl.com/3f7ddem8)

The goal of this project is to (1) detect the descriptor that influence the costumer churn and (2) build a model to predict the costumer churn.
The dataset used is availbale on Kaggle: https://tinyurl.com/ud43n28s


#### Summary:
### 1. Introduction
### 2. Data exploration
### 3. Data preprocessing
### 4. Model building and assessment

## 1. Introduction
### What is costumer churn ?

" customer churn occurs when customers or subscribers stop doing business with a company or service. Also known as customer attrition, customer churn is a critical metric because it is much less expensive to retain existing customers than it is to acquire new customers " - Molly Galetto (https://tinyurl.com/yjs9shrk)



Customer churn is a critical metric for banks. In this project, I will dig into the data, visualise them and build a model to predict the costumer churn. I will use a random forest and logistic regression algorithm.

## 2. Data exploration 

### Data visualisation

First, I look at the proportion of customers who left the company on this dataset:

![donut_churn_percent](Results/donut_churn_percent.png)

It appears that 20.4% of the customers left the bank in this dataset. We can see an ovwerrepresentation of the retained costumers in this dataset, this imbalance can bias the modeling.

## Categorical variables 

Here, the catgorical variables gives us some interresting information:
- The churn rate is higher for women than men
- The churn rate is higher for the german costumers (highest churn rate). French and Spanish customers have the same churn rate. It could be interesting to put the spanish and the french in the same group.
- Having a credit do not to be a key feature for the customer churn
- As expected, non-active members present a higher chrun rate.

