# Telco Customer Churn Analysis – Power BI

![Power BI](https://img.shields.io/badge/Tool-Power%20BI-yellow)
![Data Analysis](https://img.shields.io/badge/Skill-Data%20Analysis-blue)
![Customer Churn](https://img.shields.io/badge/Domain-Customer%20Churn-red)
![Business Analytics](https://img.shields.io/badge/Focus-Business%20Analytics-green)
![Completed](https://img.shields.io/badge/Status-Completed-brightgreen)

---

## 📊 Project Overview

This project analyzes customer churn in a telecommunications company using Microsoft Power BI.

The objective of this project is to understand customer behavior, identify the major factors contributing to customer churn, and provide meaningful business insights through an interactive dashboard.

The analysis focuses on customer demographics, service subscriptions, contracts, billing information, tenure, and churn patterns.

---

## 🎯 Objectives

* Analyze the overall customer churn rate.
* Identify customer segments with high churn rates.
* Understand the relationship between services and customer churn.
* Analyze customer contracts and billing patterns.
* Study churn across different tenure groups.
* Analyze monthly charges and customer behavior.
* Identify factors that may contribute to customer attrition.
* Present actionable business insights through an interactive Power BI dashboard.

---

## 🛠️ Tools & Technologies

* Microsoft Power BI
* Power Query
* DAX
* Data Cleaning
* Data Transformation
* Data Analysis
* Data Visualization
* Excel / CSV

---

## 📁 Dataset

The dataset contains customer-level information related to telecommunications services.

### Key Features

* Customer ID
* Gender
* Senior Citizen
* Partner
* Dependents
* Tenure
* Phone Service
* Multiple Lines
* Internet Service
* Online Security
* Online Backup
* Device Protection
* Tech Support
* Streaming TV
* Streaming Movies
* Contract
* Paperless Billing
* Payment Method
* Monthly Charges
* Total Charges
* Churn

---

## 🧹 Data Preparation

The dataset was prepared using Power Query before creating the dashboard.

The main data preparation steps included:

* Removing unnecessary columns
* Checking and handling missing values
* Correcting data types
* Cleaning categorical values
* Creating meaningful customer segments
* Creating tenure groups
* Preparing the dataset for analysis and visualization

---

## 📐 Key Measures

### Total Customers

```DAX
Total Customers =
DISTINCTCOUNT(Customers[customerID])
