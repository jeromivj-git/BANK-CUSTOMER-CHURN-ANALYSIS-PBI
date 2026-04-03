# 💳 Bank Customer Churn Analysis (Power BI)

## 📌 Project Overview
The Bank Customer Churn Analysis project leverages Power BI to analyze customer data and identify patterns that lead to customer attrition. The dataset includes attributes such as credit score, geography, age, tenure, balance, and activity status. The project focuses on transforming raw data into meaningful insights through data cleaning, modeling, and visualization. Interactive dashboards and DAX measures are used to monitor KPIs and support data-driven decision-making to improve customer retention.

---

## 🎯 Project Objectives
- Analyze customer data to identify churn patterns and trends  
- Determine key factors influencing customer attrition  
- Segment customers based on demographics and behavior  
- Identify high-risk customers likely to churn  
- Build interactive dashboards for monitoring KPIs  
- Provide data-driven recommendations to improve retention  

---

## 📂 Data Source
- Source: Maven Analytics – Bank Customer Churn Dataset  
- Timeline: 2020–2025  
- Domain: Banking / Customer Analytics  
- Data includes customer demographics, financial details, and churn status  

---

## 🛠️ Tools & Technologies
- **Microsoft Excel** – Data cleaning, transformation, pivot tables  
- **Power Query** – Data preprocessing  
- **Power BI** – Data modeling, DAX calculations, dashboard creation  

---

## 🧹 Data Pre-Processing
- Removed duplicates and null values  
- Standardized column formats and data types  
- Created derived columns (Age Group, Balance Group)  
- Filtered irrelevant records  
- Performed initial analysis using pivot tables  
- Converted data into structured format for modeling  

---

## 🧩 Data Modeling
- Implemented **Star Schema Architecture**  
- Fact Table: `Fact_CustomerChurn`  
- Dimension Tables: `Dim_AgeGroup`, `Dim_BalanceGroup`, `Dim_Geography`  
- Established **Many-to-One relationships**  
 

---

## 🔍 Exploratory Data Analysis
- Analyzed customer distribution across geography  
- Evaluated churn trends by age, tenure, and balance  
- Compared churn rates across gender and activity status  
- Identified high-risk customer segments  
- Examined relationship between products and churn  

---

## 📊 Key Visualizations
- KPI Cards (Total Customers, Churn Rate)  
- Bar Charts (Churn by Geography, Gender)  
- Donut Charts (Customer Segments)  
- Line Charts (Churn Trends)  
- Slicers (Age Group, Balance Group)  

---

## 💡 Key Insights
- Customers aged 30–50 show higher churn rates  
- High balance customers are more likely to churn  
- Germany has higher churn compared to other regions  
- Inactive customers have significantly higher churn  
- Customers with fewer products are more likely to leave  

---

## ✅ Recommendations
- Target high-risk customers with personalized offers  
- Improve engagement strategies for inactive customers  
- Promote additional products to increase retention  
- Focus retention campaigns on high-churn regions  
- Develop loyalty programs for long-term customers  

---

## ▶️ How to Use
1. Load dataset into Excel or Power BI  
2. Perform data cleaning using Power Query  
3. Build data model (fact and dimension tables)  
4. Create DAX measures for KPIs  
5. Develop dashboards in Power BI  
6. Use insights to support business decisions  

---
