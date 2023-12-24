# Online-Fraud-Payment-Detection
This repository contains Online Fraud Payment Detection project using Python, ML and exploratory data analysis.
<br> 
Author - Souyash Dutta

## Introduction
With the rapid growth of e-commerce and online transactions, the need for robust security measures to combat fraudulent activities has become paramount. The "Online Fraud Payment Detection" project addresses this critical concern by leveraging advanced data science techniques to identify and prevent fraudulent transactions in real-time.

As online payment platforms continue to evolve, so do the methods employed by fraudsters to exploit vulnerabilities. This project aims to develop a sophisticated predictive model that can analyze transactional data, detect irregular patterns, and provide instantaneous alerts to mitigate potential risks. By combining cutting-edge machine learning algorithms with comprehensive data analysis, the goal is to create a proactive defense system that safeguards both businesses and consumers from financial fraud.

### Objective  
**To train machine learning models for identifying fraudulent and non-fraudulent payments**

The dataset consists of 10 variables:
* step: represents a unit of time where 1 step equals 1 hour
* type: type of online transaction
* amount: the amount of the transaction
* nameOrig: customer starting the transaction
* oldbalanceOrg: balance before the transaction
* newbalanceOrig: balance after the transaction
* nameDest: recipient of the transaction
* oldbalanceDest: initial balance of recipient before the transaction
* newbalanceDest: the new balance of recipient after the transaction
* isFraud: fraud transaction


### Python Libraries
pandas, numpy, seaborn, matplotlib, tabulate, sklearn

Random Forest and Logistics Regression were used to identify online payment fraud due to the large dataset.
![image](https://github.com/Souyash77/Online-Fraud-Payment-Detection/assets/67053144/e2271902-a4b3-4f05-b0fe-9f7ad39f6064)


Read the complete Online Payment Fraud Detection project [here](https://github.com/Souyash77/Online-Fraud-Payment-Detection/blob/main/online-fraud-payment-detection.ipynb).

## Conclusion
The best performing model is **Random Forest** for identifying fraudulent and non-fraudulent payments.
