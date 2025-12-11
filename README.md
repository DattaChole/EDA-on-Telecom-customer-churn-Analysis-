# EDA-on-Telecom-customer-churn-Analysis-
## Project Overvie:

This project performs an in-depth Exploratory Data Analysis (EDA) on a telecom customer dataset to understand the key factors influencing customer churn.
The analysis focuses on relationships between customer demographics, service usage, account information, and billing patterns to uncover insights that help reduce churn.

## Dataset Description

The dataset includes the following key fields:

Customer Demographics

Gender

Senior citizen status

Partner & dependent status

Service Information

Phone service

Internet service

Online security, backup, streaming TV & movies

Account & Billing

Contract type

Payment method

Electronic check usage

Monthly & total charges

Tenure (customer subscription duration)

Target Variable-

Churn: Whether the customer left the company

### The dataset used in this project is available in this repository:
[Dataset Link]([https://example.com/dataset](https://github.com/DattaChole/EDA-on-Telecom-customer-churn-Analysis-/blob/main/Telecom_customer_churn.csv)

## Steps Followed
### 1. Load the Dataset

- Import the CSV file into a Pandas DataFrame

- Check the dataset shape and basic info

- Preview the top rows to understand the structure

### 2. Data Cleaning

- Handle missing values

- Fix incorrect data types (e.g., TotalCharges as numeric)

- Remove duplicates

- Treat outliers if needed

### 3. Exploratory Data Analysis (EDA)

- Univariate analysis (distribution of each column)

- Bivariate analysis (relationships with Churn)

- Correlation heatmap

- Visualize key patterns (bar charts, histograms, box plots)

### 4. Feature Understanding

- Analyze customer demographics

- Study service usage patterns

- Explore contract and billing types

- Identify high-risk churn groups

### 5. Insight Generation

- Summarize key findings

- Identify factors contributing to churn

- Suggest possible business actions

## Visuals
    1. <img width="1128" height="879" alt="Screenshot 2025-12-09 231338" src="https://github.com/user-attachments/assets/211016df-182b-4755-a2cf-26b8d8ecf7aa" />
    2.<img width="1109" height="867" alt="Screenshot 2025-12-10 132811" src="https://github.com/user-attachments/assets/7234239c-06e9-42fd-8488-c88a5af66e1f" />
    3. <img width="1151" height="900" alt="Screenshot 2025-12-10 133201" src="https://github.com/user-attachments/assets/0dc04ade-e330-43c5-b771-73f637502249" />


## Results / Key Insights
### Demographic : 
   The customers who are senior citizens or who does not have any partners or Dependents are more likely to churn.
   We need to provide offers and promotions for this type of customers.

### Internet :
   We need to investigate about the 'Fiber Optics' internet service as customers who are using fiber optics are churning at higher rate.

### Additional Service : 
   As people who didnt signed up for additional services like online security, Online Backup, Device Protection, Tech Support will churn. we can combines these additional services in a single plan so the churning will be reduced.
    
 ### Payment Method : 
   We need to check if there is some issues in Electronic Check as customers are churning at a severe rate using Electronics Check.
 
 ### contract : 
   we need to make offer on long term contract as customers having yearly based contract are more likely not to churn.
 
 ### Tenure : 
   Customers with short tenure have a high risk of leaving. 
   We need to implement some strategy to retain them.
