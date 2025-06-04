# About The Project
This project endeavors to develop a sophisticated machine-learning model aimed at accurately predicting the possibility whether the customer will churn (leave) the bank or not based on their demographic, financial, and account activity data.

The Given dataset provides a multitude of attributes including Customer IDs, current balance, Tenure, and a wealth of other pertinent features. The focal point of this endeavor centers on the Exited field  (‘Y’ status), which serves as the pivotal target variable for classification. 
To make any sort of prediction from the data, the data is first cleaned, then some EDA is performed on the data to remove any outliers and to discover any insight in the features and after applying some pre-processing techniques a classification ML model is used to figure out the Exited Status of the Customer.

# What is Customer Churn
Customer churn refers to the rate at which customers stop using a product or service, or cease to be a paying customer, over a specific period. It's essentially the loss of existing customers. 
A high churn rate indicates a business is losing customers faster than it's acquiring new ones, which can negatively impact revenue and profitability

# About The Data
The data Presented to us consists of 10000 observations and 12 features + 1 target attribute. Attributes given in dataset as:

- CustomerId: Unique identifier for each customer.
- Lastname: Customer's last name.
- CreditScore: Customer's credit rating.
- Geography: Country of the customer (France, Spain, Germany).
- Gender: Male or Female.
- Age: Customer's age.
- Tenure: Number of years the customer has been with the bank.
- Balance: Account balance.
- NumOfProducts: Number of products the customer has with the bank.
- HasCrCard: Whether the customer has a credit card (1 = Yes, 0 = No).
- IsActiveMember: Whether the customer is an active member (1 = Yes, 0 = No).
- EstimatedSalary: Customer's estimated salary.
- Exited: Target variable (1 = Churned, 0 = Stayed).

# Conclusion
Customer churn is a significant issue for banks, impacting revenue and customer lifetime value. This project has demonstrated the application of Machine Learning in identifying whether the Customer will churn or not, and how much remarkable potential it has in enhancing the accuracy of the prediction. And through the confusion matrix we saw that the train and test data is balanced. 

Through the utilization of ensemble techniques and the dataset we have seen the development of a good model that provides an accuracy of 87%. As the technology's advances, we can expect a greater stride in the accuracy and efficiency of the machine learning models which in turn will contribute to even  Reducing the churn Rate. 



