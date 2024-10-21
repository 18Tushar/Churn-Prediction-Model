
# Customer Churn Prediction

This project focuses on predicting **customer churn** for a bank using machine learning techniques. The dataset contains various features such as customer demographics, account information, and transaction history, which are used to predict whether a customer will leave the bank.

## Project Overview

Customer churn prediction is a common problem in banking, where identifying customers who are likely to leave can help banks take proactive measures to retain them. In this project, we build a machine learning model to predict whether a customer will churn based on the available demographic and financial data.

### Dataset

The dataset used for this project is sourced from [Kaggle](https://www.kaggle.com/datasets/mathchi/churn-for-bank-customers?datasetId=797699&sortBy=voteCount), consisting of 10,000 rows and 14 columns. The target variable is `Exited`, which indicates whether the customer has left the bank.

#### Data Dictionary

| Column Name       | Description                                                        |
|-------------------|--------------------------------------------------------------------|
| RowNumber         | Row number                                                         |
| CustomerId        | Unique identification key for different customers                  |
| Surname           | Customer's last name                                               |
| CreditScore       | Credit score of the customer                                       |
| Geography         | Country of the customer                                            |
| Age               | Age of the customer                                                |
| Tenure            | Number of years with the bank                                      |
| Balance           | Bank balance of the customer                                       |
| NumOfProducts     | Number of products used by the customer                            |
| HasCrCard         | Whether the customer holds a credit card (1: Yes, 0: No)           |
| IsActiveMember    | Whether the customer is an active bank member (1: Yes, 0: No)      |
| EstimatedSalary   | Customer's estimated salary                                        |
| Exited            | Whether the customer left the bank (1: Yes, 0: No)                 |

### Project Structure

- `Customer Churn Prediction.ipynb`: Jupyter notebook containing the code and analysis.
- `churn.csv`: Dataset used for training and evaluation (this needs to be added manually or loaded within the notebook).
- `README.md`: Project description and setup instructions (this file).

### Installation and Setup

To run this project locally, follow the steps below:

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/customer-churn-prediction.git
    ```

2. Navigate to the project directory:
    ```bash
    cd customer-churn-prediction
    ```

3. Open the Jupyter notebook:
    ```bash
    jupyter notebook Customer\ Churn\ Prediction.ipynb
    ```

### Data Preprocessing

The data preprocessing steps include:
- Handling missing values (if any).
- Encoding categorical variables like `Geography` and `Gender`.
- Feature scaling for variables like `CreditScore`, `Age`, `Balance`, etc.
- Splitting the data into training and testing sets.

### Model Building

Several machine learning models are tested, including:
- Logistic Regression
- Decision Trees
- Random Forest
- Support Vector Machines (SVM)

The performance of these models is evaluated based on accuracy, precision, recall, and F1-score.

### Results

- The best-performing model is chosen based on evaluation metrics. Detailed visualizations, confusion matrices, and feature importance plots are included in the notebook to provide insights into model performance.
<img src="https://github.com/user-attachments/assets/e7e66ed4-0ca7-4198-9de3-67af484a54ec" alt="Chart 1" width="400">
<img src="https://github.com/user-attachments/assets/5be468a9-10f7-4274-a8bb-ae2ad5e31ee3" alt="Chart 2" width="600">


### Conclusion

This project demonstrates how customer churn prediction can be tackled using machine learning. With the right data, banks can take informed steps to reduce churn rates and retain customers.

## Contributions

Contributions are welcome! Please feel free to submit a pull request or open an issue if you find any bugs or have suggestions for improvements.
