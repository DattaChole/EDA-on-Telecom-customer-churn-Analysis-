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
