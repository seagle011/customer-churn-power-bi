# Customer Churn Analysis in Power BI

## Overview

This project involves analyzing customer churn using Power BI. The goal is to identify patterns and insights that can help reduce customer churn for a fictional telecom company. The dataset used contains customer information such as demographics, account information, and service usage details.

## Table of Contents
1. [Introduction](#introduction)
2. [Data Source](#data-source)
3. [Objectives](#objectives)
4. [Tools and Technologies](#tools-and-technologies)
5. [Data Preparation](#data-preparation)
6. [Analysis and Visualization](#analysis-and-visualization)
7. [Key Insights](#key-insights)
8. [Conclusion](#conclusion)
9. [How to Use](#how-to-use)
10. [Acknowledgements](#acknowledgements)

## Introduction
Customer churn is a critical metric for businesses, particularly in the telecom industry. Understanding the factors that contribute to customer churn can help companies implement strategies to retain customers and improve overall satisfaction.

## Data Source
The dataset used in this analysis is sourced from the DataCamp project "Analyzing Customer Churn in Power BI". It includes information on customers such as:
- Customer ID: The unique ID that identifies a customer.
- Churn Label: Contains "Yes" or "No" to indicate if a customer churned.
- Churn Reason: The particular reason why the customer ended the contract.
- Churn Category: Groups multiple churn reasons together for analysis purposes.
- Gender:  The gender of the customer, indicated by “Male”, “Female” or “Prefer not to say”
- Under 30: Indicates if the customer is under 30 with “Yes” or “No”.
- Senior: Indicates if the customer is above 65 with “Yes” or “No”.
- Age: The age of the customer.
- Contract Type: Contains “Month-to-Month”, “One Year” or “Two Year”.
- Payment Method: Preferred payment method of the customer indicated with “Credit Card”, “Direct Debit” or “Paper Check”.
- State: The code of the state where the customer lives.
- Phone Number: Phone number of the customer
- Group:  Indicates if the customer is part of a group contract. A group contract offers advantages and is generally cheaper. Contains “Yes” or “No”.
- Number of customers in a group:  Number of customers part of the group.
- Account Lenght (in months): The number of months the customer has been with Databel.
- Local Calls:  Amount of local (within the US) calls from the customer.
- Intl Calls: Amount of international (outside the US) calls from the customer.
- Intl Mins: The number of minutes spent calling internationally. Intl Active: Indicates if the customer called internationally with a “Yes” or “No”.
- Intl Plan: Indicates if the customer has a premium plan to call internationally for free with “Yes” or “No. This premium is reflected in the amount of the monthly charge.
- Extra International Charges: Contains the extra charges for international calls for customers who are not on an international plan.
- Customer Service Calls: The number of calls made to customer service.
- Avg Monthly GB Download: Contains the average monthly download volume in gigabytes.
- Unlimited Data Plan: Indicates if the customer has free unlimited download capacity with “Yes” or “No”. This premium is reflected in the amount of the monthly charge.
- Extra Data Charges: Contains the extra charges for data downloads for customers who are not on an unlimited plan.
- Monthly Charges: Average of all Monthly Charges to the customer.
- Total Charges: Sum of all monthly charges.

## Objectives
- To identify key factors that influence customer churn.
- To visualize these factors using Power BI.
- To provide actionable insights to reduce churn rates.

## Tools and Technologies
- **Power BI:** For data visualization and analysis.
- **Excel/CSV:** For initial data handling and cleaning.
- **DataCamp:** As the platform for learning and project guidance.

## Data Preparation
1. **Data Cleaning:** Handle missing values, incorrect data entries, and duplicates.
2. **Data Transformation:** Create new calculated columns, normalize data, and categorize where necessary.
3. **Data Import:** Load the cleaned and prepared data into Power BI for analysis.

## Analysis and Visualization
- **Customer Demographics:** Visualize the distribution of customers based on age, gender, etc.
- **Service Usage:** Analyze the impact of different services on churn.
- **Account Information:** Examine how contract types, payment methods, and tenure affect churn rates.
- **Churn Analysis:** Use various visualizations to identify patterns and correlations between different variables and churn status.

## Key Insights
- Almost half of all customers churning are related to the competitor category.
- California has an extremely high churn rate.
- Churn rate for senior citiziens is somewhat higher than the average (around 10%)
- The churn rate is lowest for customers in groups of 6.
- For unlimtied plans and consumption, people who don't have an unlimited plan an consume less than 5GB of data have a low churn rate.
- While California has a high churn rate, it also has a high percentage (72%) of potential clients for international plans.
- Churn rate for monthly contracts is significantly higher.
- There is a lot of customer service calls when it comes to monthly contracts utilizing debit card payment, this subset also has a churn rate that is more than half.
- Considering that "Attitude of support person" was in the top 3 reasons for churning, and taking the above point into consideration, there seems to be a real problem with customer service in Databel.
- Although California has the highest churn rate, it also has the lowest number of customer service calls.

## Conclusion
The analysis provides a comprehensive overview of the factors affecting customer churn in the telecom industry. By understanding these factors, the company can implement targeted strategies to improve customer retention and satisfaction.


