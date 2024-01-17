# Bank Customer Churn Binary Classification Model

## Overview
This repository contains a binary classification model built to predict customer churn in the banking industry. The model is trained on the Bank Customer Churn dataset, which includes various customer attributes and whether they have churned or not.

## Dataset 

https://www.kaggle.com/competitions/playground-series-s4e1/data & https://www.kaggle.com/datasets/shubhammeshram579/bank-customer-churn-prediction

The dataset includes the following attributes:
- Customer ID: A unique identifier for each customer
- Surname: The customer's surname or last name
- Credit Score: A numerical value representing the customer's credit score
- Geography: The country where the customer resides (France, Spain, or Germany)
- Gender: The customer's gender (Male or Female)
- Age: The customer's age.
- Tenure: The number of years the customer has been with the bank
- Balance: The customer's account balance
- NumOfProducts: The number of bank products the customer uses (e.g., savings account, credit card)
- HasCrCard: Whether the customer has a credit card (1 = yes, 0 = no)
- IsActiveMember: Whether the customer is an active member (1 = yes, 0 = no)
- EstimatedSalary: The estimated salary of the customer
- Exited: Whether the customer has churned (1 = yes, 0 = no)

## Data Quality Assurance with Great Expectations (GX)
To maintain high data quality and ensure that the datasets used for training and evaluation are reliable, we use [Great Expectations (GX)](https://greatexpectations.io/). Great Expectations is an open-source library that provides a framework for defining and enforcing data quality expectations.

### Why Use Great Expectations?
- **Data Validation**: Great Expectations helps validate the quality and consistency of our datasets by defining expectations and running validation checks. This ensures that the data meets the required standards for model training and evaluation.

- **Automated Testing**: We can automate the data validation process, allowing us to easily catch and address data issues early in the pipeline, reducing errors and improving model performance.

- **Documentation**: Great Expectations provides a way to document data expectations, making it easier for team members to understand the data requirements and expectations.

- **Integration**: GX seamlessly integrates with our data pipeline, allowing us to incorporate data validation into our workflows.



## Model
We have developed a binary classification model using various machine learning techniques to predict whether a customer will churn (Exited = 1) or not (Exited = 0) based on the provided attributes. The model has been trained, tested, and evaluated to ensure its accuracy and reliability in predicting customer churn.

## Usage
To use this model, you can follow these steps:
1. Clone this repository to your local machine.
2. Install the required dependencies mentioned in the `requirements.txt` file.
3. Run the provided Jupyter notebook or Python script to load the dataset, preprocess it, and train the model.
4. Use the trained model to make predictions on new data or evaluate its performance.

## Results
We have included the model's performance metrics and evaluation results in the repository, allowing you to assess its accuracy and effectiveness in predicting customer churn.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

Feel free to explore the code and use the model for your own customer churn prediction tasks. If you have any questions or suggestions, please don't hesitate to open an issue or reach out to us.

Happy modeling!
