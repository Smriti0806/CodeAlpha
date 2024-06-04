Code Aplha task information 
# Credit Scoring Model

This project develops a credit scoring model to predict the creditworthiness of individuals based on historical financial data. The model utilizes various classification algorithms and assesses their accuracy to identify the best-performing model.

## Table of Contents

- [Introduction](#introduction)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Model Training](#model-training)
- [Model Evaluation](#model-evaluation)
- [Test Case](#test-case)
- [Contributing](#contributing)
- [License](#license)

## Introduction

The goal of this project is to create a model that can predict whether an individual is a good or bad credit risk based on their financial history. The project uses synthetic data to simulate real financial data.

## Dataset

The synthetic dataset contains various features such as:
- Status
- Duration
- Credit history
- Purpose
- Amount
- Savings
- Employment duration
- Installment rate
- Personal status and sex
- Other debtors
- Present residence
- Property
- Age
- Other installment plans
- Housing
- Number of credits
- Job
- People liable
- Telephone
- Foreign worker

The target variable is `credit_risk`, which indicates whether the individual is a good (1) or bad (0) credit risk.

## Installation

To run this project locally, follow these steps:

1. **Clone the repository**:
    ```bash
    git clone https://github.com/yourusername/credit-scoring-model.git
    cd credit-scoring-model
    ```

2. **Create and activate a virtual environment**:
    ```bash
    python -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. **Install the required packages**:
    ```bash
    pip install -r requirements.txt
    ```

## Usage

1. **Data Preparation and Model Training**:
    - The dataset is generated and preprocessed, including encoding categorical variables and scaling features.
    - Multiple classification models (e.g., Logistic Regression, Random Forest Classifier, Gradient Boosting Classifier) are trained and evaluated.

2. **Prediction**:
    - A synthetic test case representing an individual's financial profile is created.
    - The test case is encoded, scaled, and used to predict creditworthiness using the trained model.

## Model Training

The model training process involves the following steps:
1. Generating synthetic data.
2. Encoding categorical variables.
3. Splitting the data into training and testing sets.
4. Scaling the features.
5. Training multiple classification models.
6. Evaluating the models using various metrics.

## Model Evaluation

The models are evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

## Test Case

A synthetic test case is created to demonstrate how the model predicts the creditworthiness of an individual. The test case is preprocessed (encoded and scaled) and passed to the trained model for prediction. The predicted class (creditworthiness) and the associated probabilities are then printed.
