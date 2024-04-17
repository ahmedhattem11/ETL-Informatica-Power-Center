# Informatica ETL Project README

## Overview

This Informatica project involves Extracting, Transforming, and Loading (ETL) data from two CSV files: `Churn_Modelling2.csv` and `Churn_Modelling3.csv`. The objective is to perform various analyses on the data and generate specific outputs as outlined below.

## Tasks

### 1. Sum of Balances for Male and Female Customers
   - Calculate the sum of balances for male and female customers.

### 2. Number of Active Male and Female Customers
   - Determine the number of active male and female customers.

### 3. Customer Age Distribution
   - Group customers based on age distribution into the following categories:
     - Age between 18 and 30
     - Age between 30 and 45
     - Age above 45

### 4. Users with Available Balance Data
   - Identify users with available balance data (balance > 0) and rank them in ascending order.

### 5. Top 5 Balances
   - Retrieve all information for customers with the top 5 balances.

### 6. Highest and Lowest Credit Score Values
   - Find the highest and lowest credit score values.

## Outputs

- `sum_of_balances.csv`: Sum of balances for male and female customers.
- `active_customers.csv`: Number of active male and female customers.
- `age_distribution_18_30.csv`, `age_distribution_30_45.csv`, `age_distribution_above_45.csv`: Age distribution tables.
- `users_with_available_balance.csv`: Users with available balance data.
- `top_5_balances.csv`: Information for customers with the top 5 balances.
- `highest_lowest_credit_scores.csv`: Highest and lowest credit score values.

## Usage

1. Ensure Informatica PowerCenter is installed and configured.
2. Import the CSV files `Churn_Modelling2.csv` and `Churn_Modelling3.csv` into Informatica PowerCenter.
3. Create mappings, transformations, and workflows to perform the specified tasks.
4. Execute the workflows to generate the output files mentioned above.

## Note
- Ensure the input CSV files are correctly mapped within Informatica PowerCenter.
- Validate the transformations and mappings to ensure accurate data processing.
- Monitor the workflow execution for any errors or issues.
- Adjust any parameters or configurations as needed to optimize performance and accuracy.


