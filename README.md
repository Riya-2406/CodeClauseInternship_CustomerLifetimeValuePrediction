# Customer Lifetime Value Prediction

## Aim
Predict the lifetime value of customers for a business based on their historical interactions.

## Description
This project applies regression techniques to estimate the future value that a customer will bring to the business. Using a dataset of customer interactions, we preprocess the data, train a Random Forest Regressor model, and evaluate its performance. The model can then be used to predict the lifetime value of new customers.

## Technologies
- Python
- Pandas
- Scikit-learn

## Table of Contents
- [Installation](#installation)
- [Usage](#usage)
- [Features](#features)
- [Configuration](#configuration)
- [Contributing](#contributing)
- [Acknowledgements](#acknowledgements)

## Installation
To run this project, you will need Python installed on your machine. Additionally, you need to install the following Python libraries:

```bash
pip install pandas scikit-learn
```

## Usage
1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/customer-lifetime-value-prediction.git
    ```
2. Navigate to the project directory:
    ```bash
    cd customer-lifetime-value-prediction
    ```
3. Ensure you have a dataset named `customer_data.csv` in the project directory.
4. Run the script to train and evaluate the model:
    ```bash
    python Customer_lifetime_value_prediction.py
    ```
5. Review the output, including the Mean Squared Error (MSE), R² score, and predicted lifetime value for new customers.

## Features
- **Data Loading**: Load the dataset from `customer_data.csv`.
- **Preprocessing**: Convert dates, handle missing values, and encode categorical features.
- **Feature Extraction**: Extract and preprocess features for modeling.
- **Model Training**: Train a Random Forest Regressor model using Scikit-learn.
- **Model Evaluation**: Evaluate model performance using Mean Squared Error (MSE) and R² score.
- **Prediction**: Predict the lifetime value of new customers based on historical data.

## Acknowledgements
- [Scikit-learn](https://scikit-learn.org/) for the machine learning tools and algorithms used.
- [Pandas](https://pandas.pydata.org/) for data manipulation and analysis.
- The [Python community](https://www.python.org/community/) for providing a robust ecosystem for data science.

