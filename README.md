# Telecommunication-Data-Analysis
Performed EDA on this Telecommunication data to understand customer churn percentage and pattern according to services, plans etc.

## Dataset Description :


The dataset contains **7043 records** and **21 columns** related to customer information for a telecom company, aimed at analyzing customer churn. Below is a detailed description of the columns:

1. **customerID**: Unique identifier for each customer (non-null object).
2. **gender**: Customer gender (Male/Female).
3. **SeniorCitizen**: Indicates if the customer is a senior citizen (0 = No, 1 = Yes).
4. **Partner**: Whether the customer has a partner (Yes/No).
5. **Dependents**: Whether the customer has dependents (Yes/No).
6. **tenure**: Number of months the customer has stayed with the company.
7. **PhoneService**: Whether the customer has phone service (Yes/No).
8. **MultipleLines**: Whether the customer has multiple lines (Yes/No/No phone service).
9. **InternetService**: Type of internet service the customer has (DSL, Fiber optic, or No).
10. **OnlineSecurity**: Whether the customer has online security service (Yes/No/No internet service).
11. **OnlineBackup**: Whether the customer has online backup (Yes/No/No internet service).
12. **DeviceProtection**: Whether the customer has device protection (Yes/No/No internet service).
13. **TechSupport**: Whether the customer has tech support (Yes/No/No internet service).
14. **StreamingTV**: Whether the customer has streaming TV service (Yes/No/No internet service).
15. **StreamingMovies**: Whether the customer has streaming movies service (Yes/No/No internet service).
16. **Contract**: The contract type (Month-to-month, One year, Two year).
17. **PaperlessBilling**: Whether the customer is on paperless billing (Yes/No).
18. **PaymentMethod**: The payment method used by the customer (Electronic check, Mailed check, Bank transfer, Credit card).
19. **MonthlyCharges**: The amount charged to the customer per month (float).
20. **TotalCharges**: Total amount charged (stored as an object but should be numerical).
21. **Churn**: Whether the customer churned (Yes/No).

### Data Types:
- Most columns are categorical (object), except for **tenure**, **SeniorCitizen** (both int64), and **MonthlyCharges** (float64).
- **TotalCharges** is stored as a string/object but should be converted to numerical for analysis.

### Observations:
- The dataset includes a wide variety of customer services, including internet, phone, and support-related services, along with customer demographics (senior citizen, partner, dependents).
- The target variable for churn prediction is **Churn**.

## Objective :
Performed EDA to derive churn percentage and analyze various services provided in telecommunications and their impact on churn

# Python libraries used for analysis :
* Numpy
* Pandas
* Seaborn
* Matplotlib

## Analyze the following :
* Count of churn customer
* Percentage of churn customer
* Count of gender
* Gender-wise churned customers
* Count of Senior Citizen
* Churn by Senior Citizen
* Churn by Tenure
* Count and Percentage of Type of Contract
* Churn by Type of Contract
* Churn by Services
* Count of Payment Method
* Churn by Payment Method

## Performed various EDA techniques :
* Check and drop duplicated
* Replace blank with zeroes to perform calculations
* Group by columns
* Change object data type into float and int
* Created data frames
* Mapping of values
* Looping over the columns for data cleaning

## Analyze the data using the following charts :
* Pie chart
* Column chart
* Stacked column chart
* Histogram


## Analysis Files : 
| Project Name | File | My Linkedin | My Github |
|-|-|-|-|
|Telecom's Data Analysis| [File]() | [Linkedin](https://www.linkedin.com/in/shubhammeshram01/) | [Github](https://github.com/shubhammeshram01) |
