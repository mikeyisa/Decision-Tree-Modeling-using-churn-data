# Decision Tree Churn Modeling

## Overview
This project focuses on predicting customer churn in the banking sector using decision tree-based machine learning models. The project leverages powerful ensemble methods such as Random Forest and XGBoost to enhance predictive accuracy and model interpretability by exploring and optimizing various hyperparameters.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Modeling](#modeling)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Contact](#contact)

## Introduction
Customer churn is a critical metric for businesses, especially in the banking sector. Predicting churn can help banks take proactive measures to retain customers. This project builds predictive models using decision trees, Random Forest, and XGBoost to forecast customer churn.

## Dataset
The dataset used for this project is `Churn_Modelling.csv`, which contains the following columns:
- **RowNumber**: Unique identifier for each row
- **CustomerId**: Unique identifier for each customer
- **Surname**: Customer's surname
- **CreditScore**: Customer's credit score
- **Geography**: Customer's location
- **Gender**: Customer's gender
- **Age**: Customer's age
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance
- **NumOfProducts**: Number of bank products the customer is using
- **HasCrCard**: Whether the customer has a credit card
- **IsActiveMember**: Whether the customer is an active member
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Whether the customer has exited the bank

## Installation
To run this project locally, follow these steps:

1. Clone the repository:
    ```sh
    git clone https://github.com/yourusername/decision-tree-churn-modeling.git
    ```

2. Navigate to the project directory:
    ```sh
    cd decision-tree-churn-modeling
    ```

3. Install the required dependencies:
    ```sh
    pip install -r requirements.txt
    ```

## Usage
To use the model, follow these steps:

1. Load the dataset:
    ```python
    import pandas as pd
    df = pd.read_csv('Churn_Modelling.csv')
    ```

2. Run the Jupyter Notebook to train the model:
    ```sh
    jupyter notebook Decision_tree_churn_modeling.ipynb
    ```

3. Follow the steps in the notebook to preprocess the data, train the model, and make predictions.

## Modeling
The project involves the following steps to build and evaluate the churn prediction model:
1. **Data Preprocessing**: Handling missing values, encoding categorical variables, and scaling numerical features.
2. **Feature Selection**: Selecting relevant features for the model.
3. **Model Training**: Training decision tree models and tuning hyperparameters.
4. **Ensemble Methods**: Utilizing Random Forest and XGBoost for enhanced performance.
5. **Model Evaluation**: Evaluating model performance using metrics such as F1 score, recall, precision, and accuracy. Confusion matrices are used to visually summarize the performance.

## Results
The results of the model are evaluated based on accuracy, precision, recall, and F1-score. Detailed results and model performance metrics are provided in the Jupyter Notebook.

## Contributing
Contributions are welcome! Please read the [contributing guidelines](CONTRIBUTING.md) first. You can submit issues or fork the project and create a pull request.

## License
This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact
- **Name**: Michael Yisa
- **LinkedIn**: [Michael Yisa](https://www.linkedin.com/in/michael-yisa-382a9b249)

Feel free to explore the project, raise issues, and contribute!
