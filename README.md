# Customer-Churn-Prediction
A Machine Learning Model To Predict Customer Churn


![download (3)](https://github.com/codeayiku/Customer-Churn-Prediction/assets/149838492/53fe82df-a169-426d-9796-bfb7b87e7d33)

## Table of Contents
1. [Introduction](#introduction)
2. [Data Overview](#data-overview)
3. [Key Insights](#key-insights)
   - [Churn Rate](#churn-rate)
   - [Demographic Analysis](#demographic-analysis)
   - [Service Utilization](#service-utilization)
   - [Contract Types](#contract-types)
   - [Payment Methods](#payment-methods)
4. [Visualizations](#visualizations)
5. [Power BI Dashboard](#power-bi-dashboard)
6. [Technologies Used](#technologies-used)
7. [Future Work](#future-work)
8. [Contributing](#contributing)
9. [License](#license)

## Introduction
The Customer Churn Analysis provides insights into customer behavior and patterns that lead to churn in a subscription-based business. This analysis aims to identify key factors influencing customer retention and provide actionable insights for reducing churn rates.

## Data Overview
The dataset includes information about customers, their demographics, service usage, and billing information. The data was cleaned and prepared for analysis to ensure accuracy and relevance.

### Key Columns:
- **customerID**: Unique identifier for each customer.
- **gender**: Gender of the customer.
- **SeniorCitizen**: Indicates if the customer is a senior citizen.
- **Partner**: Indicates if the customer has a partner.
- **Dependents**: Indicates if the customer has dependents.
- **tenure**: Number of months the customer has stayed with the company.
- **PhoneService**: Indicates if the customer has phone service.
- **MultipleLines**: Indicates if the customer has multiple lines.
- **InternetService**: Type of internet service the customer has.
- **OnlineSecurity**: Indicates if the customer has online security service.
- **OnlineBackup**: Indicates if the customer has online backup service.
- **DeviceProtection**: Indicates if the customer has device protection.
- **TechSupport**: Indicates if the customer has tech support.
- **StreamingTV**: Indicates if the customer has streaming TV service.
- **StreamingMovies**: Indicates if the customer has streaming movies service.
- **Contract**: Type of contract the customer has.
- **PaperlessBilling**: Indicates if the customer has paperless billing.
- **PaymentMethod**: Payment method used by the customer.
- **MonthlyCharges**: Monthly charges for the customer.
- **TotalCharges**: Total charges incurred by the customer.
- **Churn**: Indicates if the customer has churned.
- **tenure_bins**: Binned tenure for easier analysis.

## Key Insights

### Churn Rate
- **Overall Churn Rate**: Percentage of customers who churned.
- **Churn by Tenure**: Churn rate across different tenure bins.

### Demographic Analysis
- **Gender**: Churn rate by gender.
- **Senior Citizen**: Churn rate among senior citizens.
- **Dependents**: Impact of dependents on churn.

### Service Utilization
- **Phone Service**: Churn rate based on phone service usage.
- **Internet Service**: Churn rate across different internet service types.
- **Value-Added Services**: Churn rate based on usage of online security, online backup, device protection, and tech support.

### Contract Types
- **Month-to-Month**: Churn rate for month-to-month contracts.
- **One Year**: Churn rate for one-year contracts.
- **Two Year**: Churn rate for two-year contracts.

### Payment Methods
- **Electronic Check**: Churn rate for electronic check payments.
- **Mailed Check**: Churn rate for mailed check payments.
- **Bank Transfer**: Churn rate for bank transfer payments.
- **Credit Card**: Churn rate for credit card payments.

## Visualizations

### Churn Rate
- **Pie Chart**: Overall churn rate.
- **Bar Chart**: Churn rate by tenure bins.

### Demographic Analysis
- **Bar Chart**: Churn rate by gender.
- **Bar Chart**: Churn rate among senior citizens.
- **Bar Chart**: Churn rate by dependents.

### Service Utilization
- **Bar Chart**: Churn rate by phone service usage.
- **Bar Chart**: Churn rate by internet service type.
- **Bar Chart**: Churn rate by value-added services.

### Contract Types
- **Bar Chart**: Churn rate by contract type.

### Payment Methods
- **Bar Chart**: Churn rate by payment method.

## Power BI Dashboard
The Power BI dashboard provides an interactive interface to explore the customer churn dataset. Key features include:
- **Filters**: Easily filter data by Gender, Senior Citizen, Dependents, and Contract Type.
- **Interactive Charts**: Dynamic visualizations that update based on selected filters.
- **Cards**: Quick stats including Overall Churn Rate, Total Customers, and Churned Customers.

### How to Use the Dashboard
1. Open the Power BI file (`Customer_Churn_Analysis.pbix`).
2. Use the filters at the top to narrow down the data.
3. Hover over charts for detailed insights.
4. Click on segments of the charts to see related data updates.

## Technologies Used
- **Python**: For data cleaning and preprocessing.
- **Pandas**: For data manipulation.
- **Matplotlib & Seaborn**: For creating visualizations.
- **Power BI**: For interactive dashboard creation.
- **VSCode**: For code development and version control.

## Future Work
- **Predictive Modeling**: Use machine learning models to predict customer churn.
- **Customer Segmentation**: Identify customer segments most likely to churn.
- **Sentiment Analysis**: Analyze customer feedback to understand churn reasons.

## Contributing
We welcome contributions to enhance the analysis and insights. Please fork the repository and create a pull request with detailed changes.

## License
This project is licensed under the GNU General Public License v3.0 - see the [GNU General Public License v3.0](#LGNU General Public License v3.0) file for details.

