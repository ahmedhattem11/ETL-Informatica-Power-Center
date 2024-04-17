# Informatica ETL Project

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

## Screenshots
### 1. Sum of Balances for Male and Female Customers
 ![Screenshot 2024-04-17 174644](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/ef5eab00-4b51-48c1-92fc-7b02413f5977)
 
### 2. Number of Active Male and Female Customers
 ![Screenshot 2024-04-17 174728](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/13ed6b8b-af08-4c47-ab1b-f542bb809dcf)

 ### 3. Customer Age Distribution
 ![Screenshot 2024-04-17 174912](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/a286a3d5-a5aa-4c52-ba8b-9cc15637e2a4)
 
### 4. Users with Available Balance Data
![Screenshot 2024-04-17 174950](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/4e6fb19d-4bc9-456f-b9df-202926e6b6c7)

### 5. Top 5 Balances
![Screenshot 2024-04-17 175032](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/ec29d678-4101-465a-a104-4a0d14174f40)

### 6. Highest and Lowest Credit Score Values
![Screenshot 2024-04-17 174835](https://github.com/ahmedhattem11/ETL-Informatica-Power-Center/assets/87239054/4571e2b2-3db6-4905-9caa-cba93a74149b)

## Outputs

- `SumBalance_M_F.txt`: Sum of balances for male and female customers.
- `Count_Active.txt`: Number of active male and female customers.
- `Age distribution tables`.
- `Balance_Sorter.txt`: Users with available balance data.
- `Rank_Balance.txt`: Information for customers with the top 5 balances.
- `max_min_score.txt`: Highest and lowest credit score values.

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


