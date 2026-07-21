# IBM-Telco-Customer-Churn-Analysis
An end-to-end customer churn analysis using Power BI, Power Query, and DAX to discover churn sources and gain business insights.

## 📖 Project Overview
Customer churn is a major challenge for subscription-based businesses because losing customers directly impacts revenue and growth. By understanding why customers leave, companies can enhance satisfaction and create better retention strategies.This project examines customer churn using the IBM Telco Customer Churn dataset. The data was cleaned and transformed with Power Query, analyzed with DAX measures, and visualized in Power BI through interactive dashboards. The aim was to identify key factors driving churn and deliver actionable insights to help improve business decisions.

## 🎯 Business Problem
Customer churn is a critical issue for telecommunication companies, as retaining existing customers is typically more cost-effective than acquiring new ones.The company needs to identify which customers are most at risk of churning, understand the key factors driving customer attrition, and develop data-driven strategies to boost retention and minimize revenue loss.

## 🎯 Business objetives

This project aims to:

- Determine the overall customer churn rate.
- Identify customer segement with the highest churn.
- Analyxe how customer demoggrapics, contract types, internet services, payment methods and tenure influence churn.
- Identify the key drivers of customer churn.
- Provide actionable recommendations to improve customer retention.

## 📊 Business Questions

This analysis was conducted to answer the following questions:

1. What is the overall churn rate?

2. Which contract type has the higest churn rate?

3. Doest internet service influence customer churn?

4. Does Tech support reduce customerchurn?

5. Which payment method is associated with the highest churn?

6. Which customer tenure group has the highest churn?

7. Are senior citizens more likely to churn?

8. Does having a partner affect customer churn?

9. Does having dependents affect customer churn?

10. Does gender influence customer churn?

## 📁 Dataset

**Dataset:** IBM Telco Customer Churn Dataset

**Source:** Kaggle – IBM Sample Data

**Number of Rows:** 7,043

**Number of Columns:** 21

The dataset contains customer demographic information, account details, subscribed services, payment methods, tenure, monthly charges, total charges, and churn status.

 ## 🛠️ Tools Used

## 🛠️ Skills Demonstrated

### Data Analysis
- Data Cleaning and Transformation
- Exploratory Data Analysis
- Customer Churn Analysis
- Customer Segmentation
- Business Analysis

### Power BI
- Data Modeling
- DAX Calculations
- KPI Development
- Interactive Dashboard Design
- Data Visualization
- Slicers and Filters

### Business Intelligence
- Identifying Churn Drivers
- Extracting Business Insights
- Data Storytelling
- Developing Business Recommendations
- Supporting Data-Driven Decision Making

## 🧹 Data Cleaning & Transformation

The following data preparation steps were performed using **Power Query**:

* Verified and corrected data types.
* Checked for duplicate records.
* Identified missing values in the `TotalCharges` column.
* Replaced missing `TotalCharges` values with `0` for customers with zero tenure.
* Created a **Tenure Group** column to segment customers into:

  * New Customers
  * Growing Customers
  * Loyal Customers
  * Long-term Customers
* Standardized categorical values for consistent reporting.
* Validated data quality (100% valid records after cleaning).

## 📐 KPI Measures

The following DAX measures were created:

* **Total Customers**
* **Churn Rate (%)**
* **Average Tenure (Months)**
* **Total Monthly Revenue**

These measures were used to build the executive dashboard and customer analysis pages.

## 📊 Dashboard Overview

The Power BI report contains **two interactive pages**.

### Page 1 – Executive Dashboard

This page provides a high-level overview of customer churn, including:

* Total customers
* Churn rate
* Monthly revenue
* Average tenure
* Customer status (Retained vs. Churned)
* Churn by contract type
* Churn by internet service
* Churn by tech support
* Executive insights

### Page 2 – Customer Analysis

This page focuses on customer segmentation and churn behavior across:

* Payment method
* Tenure group
* Senior citizen status
* Partner status
* Dependents
* Gender

Interactive slicers were added to allow users to filter the dashboard dynamically.

## 📊 Dashboard Preview

### Executive Dashboard

<img width="760" height="472" alt="Executive_dashboard" src="https://github.com/user-attachments/assets/c98f9afc-353a-49ec-bb25-ab4c6c7d2411" />


### Customer Analysis

<img width="763" height="494" alt="Customer_analysis" src="https://github.com/user-attachments/assets/554a05ba-fc72-49b5-a688-d4766163415a" />


💡 Key Insights
The analysis identified several key factors associated with customer churn:

- **Month-to-month customers** had the highest churn rate at approximately **42%**, making them the highest-risk contract group.
- **New customers** had the highest churn rate at approximately **47%**, indicating that the early customer experience is critical for retention.
- **Fiber optic customers** had a churn rate of approximately **42%**, compared with approximately **19% for DSL customers**.
- Customers **without Tech Support** had a significantly higher churn rate than customers with Tech Support.
- Customers using **Electronic Check** had the highest churn rate among the payment methods analyzed, at approximately **45%**.
- **Senior citizens** had a churn rate of approximately **42%**, compared with approximately **24% among non-senior customers**.
- Customers **without a partner** had a higher churn rate than customers with a partner.
- Customers **without dependents** had a higher churn rate than customers with dependents.
- **Gender showed little difference in churn**, with male and female customers having similar churn rates.

## 🎯 Business Recommendations


Based on the findings from the customer churn analysis, the following recommendations are proposed:

### 1. Encourage Long-Term Contracts

Month-to-month customers have the highest churn rate at approximately 42%. The company should encourage customers to move to one-year or two-year contracts by offering loyalty rewards, discounts, or additional benefits.

**Expected Impact:** Reduce churn among high-risk month-to-month customers and improve long-term customer retention.

### 2. Improve New Customer Onboarding

New customers have the highest churn rate at approximately 47%. The company should introduce a structured onboarding program that includes welcome communication, regular check-ins, and customer education during the first year.

**Expected Impact:** Improve the early customer experience and reduce customer churn during the first stages of the customer relationship.

### 3. Promote Tech Support Services

Customers without Tech Support have a higher churn rate than customers with Tech Support. The company should consider bundling Tech Support with internet plans or offering free trials.

**Expected Impact:** Increase customer satisfaction and reduce churn among customers who may need additional technical assistance.

### 4. Encourage Automatic Payment Methods

Customers using Electronic Check have the highest churn rate among the payment methods analyzed. The company should encourage customers to switch to automatic payment methods by offering incentives and making the enrollment process easier.

**Expected Impact:** Improve payment consistency and potentially increase customer retention.

### 5. Review Fiber Optic Customer Experience

Fiber optic customers have a significantly higher churn rate than DSL customers. The company should investigate possible causes, including service quality, pricing, network reliability, and customer complaints.

**Expected Impact:** Identify and address issues affecting one of the highest-risk customer groups.

### 6. Develop Targeted Retention Strategies for Senior Citizens

Senior citizens have a higher churn rate than non-senior customers. The company should consider providing simplified service plans, dedicated customer support, and personalized retention offers.

**Expected Impact:** Improve customer satisfaction and retention among this higher-risk demographic.

### 7. Focus on High-Risk Customer Segments

The company should combine the identified churn drivers to identify customers who may be at higher risk of leaving. Customers with multiple risk factors could receive proactive retention campaigns before they decide to churn.

**Expected Impact:** Allow the company to focus retention resources on customers who are most likely to leave.


## 🧠 Skills Demonstrated

* Data Cleaning & Transformation
* Data Validation
* DAX Calculations
* KPI Development
* Data Modeling
* Dashboard Design
* Customer Segmentation
* Churn Analysis
* Business Intelligence Reporting
* Data Storytelling

## 🚀 Future Improvements

* Build a predictive churn model using machine learning.
* Create a customer risk scoring system.
* Add revenue impact analysis for churned customers.
* Integrate time-series analysis for churn trends.
* Deploy the dashboard to the Power BI Service for online access.

## 👩‍💻 About the Author

**Janet Owobi**

Aspiring Data Analyst with skills in **Power BI, Power Query, DAX, Excel, and business analysis**.

* **LinkedIn:** www.linkedin.com/in/janet-owobi-amao-data-analyst-0585b4250
* **GitHub:** : https://github.com/janetowobi8-kul



