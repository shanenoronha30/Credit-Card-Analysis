# **Credit Card Analysis Project**  
🚀 **Comprehensive Dashboard for Credit Card Performance Monitoring**  

## **Project Objective**  
This project aims to develop a comprehensive, real-time weekly dashboard for analyzing credit card transactions, customer data, and key performance metrics (KPIs). The dashboard provides actionable insights to stakeholders, enabling them to monitor and optimize the performance of credit card operations effectively.

---

## **Key Objectives**  

1. **KPI Monitoring**:  
   Measure critical KPIs such as:  
   - Revenue Generated  
   - Transaction Volume  
   - Total Interest Earned  
   - Delinquency Rate  
   - Customer Acquisition Cost (CAC)  
   - Customer Satisfaction Score  

2. **Revenue Analysis**:  
   - Analyze revenue across quarters, months, and weeks to uncover trends, seasonality, and customer spending fluctuations.  

3. **Customer Spending and Card Category Analysis**:  
   - Explore spending behavior across different card categories (Gold, Platinum) and expense types (Bills, Entertainment, Travel).  

4. **Customer Demographics Analysis**:  
   - Segment revenue based on customer attributes like age group, educational level, job type, and income level to gain targeted insights.  

5. **Week-on-Week Revenue Comparison**:  
   - Compare weekly revenue changes, detect anomalies, and identify growth opportunities.  

---

## **Tech Stack Used**  
- **PostgreSQL** for data storage and management.  
- **Power BI** for real-time data visualization and dashboard creation.  

---

## **Data Understanding**  
The dataset consists of credit card transactions and customer details, enabling in-depth analysis of spending patterns and customer profiles. 
- Dataset link:https://drive.google.com/drive/folders/1epR5h9QF7PbMwH7G28NNiHOkhgnVxBco

---

## **Project Workflow**  

### **1. Database Setup**  
- Created a data repository in PostgreSQL.  
- Built tables for **Transaction** and **Customer** data.  

### **2. Data Import**  
- Imported raw CSV data into PostgreSQL tables for structured analysis.  

### **3. Data Cleaning and Transformation**  
- Removed inconsistencies and ensured data integrity.  
- Aggregated and transformed data to facilitate analysis.  

### **4. Connecting PostgreSQL with Power BI**  
- Established a direct connection between PostgreSQL and Power BI for real-time data visualization.  

### **5. Data Preparation**  
- Created custom columns and measures in Power BI using DAX queries, such as:  
  - **Revenue** (Transaction Amount + Interest Earned + Annual Fees)  
  - **Week-on-Week Revenue Change**  
  - **Customer Acquisition Cost (CAC)**  
  - **Average Utilization Ratio (AU Ratio)**  
  - **Delinquency Rate**  

---

## **Dashboards**  

### **1. Credit Card Financial Report**  
**Key Features:**  
- KPI Monitoring  
- Revenue Analysis by Timeframe (Quarterly, Monthly, Weekly)  
- Revenue Segmentation by Age Group, Card Category, and Expenditure Type  
- Interactive Filters for dynamic data exploration
- ![image](https://github.com/user-attachments/assets/012fce0b-d4b2-486b-9dfb-77e30ce81a02)


### **2. Credit Card Customer Report**  
**Key Features:**  
- Week-on-Week Revenue Change  
- Demographic Analysis (Gender, Education, Job Type, Income Level)  
- Top 5 States Contribution  
- Interactive Tree Maps for visual representation
- ![image](https://github.com/user-attachments/assets/d0156ab2-a475-421b-81a4-7a74cc8f2d1b)


---

## **Insights**  

### **Week 53 Insights**  
- **Revenue Growth**: Increased by 28.8% compared to the previous week.  
- **Customer Growth**: Increased by 12.8% compared to the previous week.  
- **Transaction Count**: Increased by 3.39% compared to the previous week.  
- **Transaction Amount**: Increased by 35% compared to the previous week.  

### **Year-to-Date (YTD) Overview**  
- **Total Revenue**: $57 million  
- **Total Interest Earned**: $8 million  
- **Cost-to-Revenue Ratio**: 1.74%  
- **Activation Rate**: 57.5%  
- **Delinquency Rate**: 6.06%  
- **Average Utilization Ratio**: 13.47%  
- **Customer Satisfaction Score**: 3.19 out of 5  

### **Customer Spending and Transaction Patterns**  
- **Age Group Contribution**: Customers aged 40-50 contribute 43.7% of total revenue ($25M).  
- **Card Contribution**: Blue and Silver cards account for 93% of total transactions.  
- **Popular Transaction Method**: Swipe method (66.9% of all transactions).  

### **Demographic Insights**  
- **Revenue by Gender**:  
  - Male: 54.4% ($31M)  
  - Female: 45.6% ($26M)  
- **Top 3 States Contribution**: Texas (TX), New York (NY), and California (CA) contribute 68% of total revenue.  
- **Educational Level**: Graduates contribute 40.3% of total revenue.  
- **Job Type**: Business professionals contribute 31.3% of total revenue.  
- **Income Level**: High-income customers contribute 49% of total revenue.  
- **Marital Status**: Married customers contribute 50.6% of total revenue.  
- **Personal Loan Status**: Customers without personal loans contribute 87.42% of total revenue.  

---

## **How to Use This Project**  

1. Clone this repository to your local machine.  
2. Import the dataset into PostgreSQL using the provided SQL scripts.  
3. Open the Power BI reports and connect them to the PostgreSQL database.  
4. Explore the dashboards to analyze credit card transaction data and gain valuable insights.
