# Bank Customer Churn Model

This repository contains a comprehensive project focused on predicting customer churn for a bank using machine learning techniques. The aim is to identify customers who are likely to leave the bank and understand the factors influencing their decision.

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Results](#results)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Overview

Customer churn is a critical issue for many businesses, including banks. Predicting which customers are at risk of leaving allows banks to take proactive measures to retain them. This project utilizes a machine learning model to predict customer churn based on various features such as account information, transaction history, and customer demographics.

## Data

The dataset used in this project is sourced from [Kaggle's Bank Customer Churn Dataset](https://www.kaggle.com/adammaus/predicting-churn-for-bank-customers). It contains the following features:

- **CustomerID**: Unique identifier for each customer
- **Surname**: Customer's last name
- **CreditScore**: Credit score of the customer
- **Geography**: Country of the customer
- **Gender**: Gender of the customer
- **Age**: Age of the customer
- **Tenure**: Number of years the customer has been with the bank
- **Balance**: Account balance of the customer
- **NumOfProducts**: Number of bank products the customer is using
- **HasCrCard**: Whether the customer has a credit card (1 = Yes, 0 = No)
- **IsActiveMember**: Whether the customer is an active member (1 = Yes, 0 = No)
- **EstimatedSalary**: Estimated salary of the customer
- **Exited**: Whether the customer has exited the bank (1 = Yes, 0 = No)

## Installation

To get started with this project, clone the repository and install the required dependencies:

```bash
git clone https://github.com/RohitMukkala/BANK-CUSTOMER-CHURN-MODEL.git
cd BANK-CUSTOMER-CHURN-MODEL
pip install -r requirements.txt
