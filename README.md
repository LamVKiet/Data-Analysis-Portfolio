# 📊 Data Analysis Portfolio
## About

Hi, I’m Kiệt - a final-year student pursuing a Bachelor’s degree in Data Science. Throughout my academic journey, I have cultivated strong analytical thinking skills and developed proficiency in SQL, Python, and Power BI. I have hands-on experience with DAX and Power Query for data manipulation and visualization, as well as expertise in data modeling, and diagnostics.

My background includes applying predictive analytics using machine learning techniques such as regression, clustering, and classification. I have gained extensive experience in various types of analytics: descriptive, diagnostic, predictive, and prescriptive, employing both quantitative and qualitative methods.

I am particularly passionate about storytelling with data-transforming complex datasets into actionable business insights that drive data-driven decision-making. I enjoy exploring new data analysis tools and techniques, always seeking opportunities to expand my knowledge and enhance my skills. Whether working independently or collaboratively, I am motivated by excitement of uncovering valuable insights and using data to solve complex business challenges.

My CV in [pdf].

This is a repository to showcase skills, share projects and track my progress in Data Analytics / Data Science related topics.

## Table of Contents
- [About](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#about)
- [Portfolio Projects](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#portfolio-projects)
  - Python
    - [Customer Segmentation with RFM: Two Approaches Using Quintiles and K-Means Clustering](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#-customer-segmentation-with-rfm-two-approaches-using-quintiles-and-k-means-clustering)
    - [Data-Driven Digital Marketing Strategy for Sanest: From Market Insights to Multichannel Execution](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#-data-driven-digital-marketing-strategy-for-sanest-from-market-insights-to-multichannel-execution)
    - [Sentiment Analysis Application](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#sentiment-analysis-application)
  - SQL
    - [Warehouse Management System – Electronics Distribution Company](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#warehouse-management-system--electronics-distribution-company)
    - [Profitability Diagnostics & Loss Root Cause Analysis Using Advanced SQL](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#profitability-diagnostics--loss-root-cause-analysis-using-advanced-sql)
  - Power BI
    - [Store Sales Dashboard](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#store-sales-dashboard)
  - Excel
    - [Product Dashboard](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#product-dashboard)
- [Education](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#education)
- [Contact](https://github.com/LamVKiet/Data-Analysis-Portfolio/blob/main/README.md#contact)
## Portfolio Projects
In this section I will list data analytics projects briefly describing the technology stack used to solve cases.

### Python

#### **📌 Customer Segmentation with RFM: Two Approaches Using Quintiles and K-Means Clustering**

**`Code:`** [Customer Segmentation with RFM: Two Approaches Using Quintiles and K-Means Clustering.ipynb](https://github.com/LamVKiet/RFM-ANALYSIS-QUINTILES-KMEANS-PYTHON/blob/main/RFM-Analysis-Quintiles-KMeans-Python.ipynb)

**`Goal:`** 
- Implement an RFM analysis model for behavior-based customer segmentation using a pizza store dataset, applying two methods:

  - RFM with K-Means Clustering
  - RFM with Quintile-Based Scoring

**`Description:`** Conducted customer segmentation using the RFM (Recency, Frequency, Monetary) model on transactional data from a pizza store. The project applies two different approaches: quintile-based scoring and unsupervised machine learning (K-Means Clustering). The objective is to classify customers into meaningful segments to support personalized marketing strategies and enhance customer retention.

**`Results:`** 
- Identified key customer segments using two methods: Quintile-based scoring and K-Means clustering.
- Proposed personalized marketing strategies such as retention offers and targeted campaigns for each segment to optimize revenue and enhance customer satisfaction.

#### **📌 Data-Driven Digital Marketing Strategy for Sanest: From Market Insights to Multichannel Execution**
**`Link:`** [Data-Driven Digital Marketing Strategy for Sanest: From Market Insights to Multichannel Execution](https://github.com/LamVKiet/Sanest-Digital-Marketing-Strategy)

**`Goal:`** To enhance Sanest’s brand visibility, customer engagement, and online sales through a data-driven, multichannel digital marketing strategy.

**`Description:`** To develop a comprehensive, data-driven digital marketing strategy for Sanest, with a focus on:

- Defining clear business and marketing objectives

- Conducting in-depth market and consumer research

- Analyzing Sanest’s current marketing performance and positioning

- Develop effective branding and multichannel communication strategies.

**`Results:`**
- Developed a data-driven multichannel strategy tailored to Sanest's customer segments.

- Identified key customer insights and market opportunities through consumer behavior analysis.

- Delivered a one-year actionable marketing plan with SMART goals and KPI tracking.

- Proposed optimized content plans and platform-specific strategies to enhance engagement.

- Created templates for landing pages and email campaigns to support brand communication.

#### **📌Sentiment Analysis Application**

**`Link:`** [Sentiment Analysis Application.ipynb](https://github.com/LamVKiet/SENTIMENT-ANALYSIS-APPLICATION)

**`Goal:`** Perform sentiment analysis by classifying reviews with a rating above 3 as "Positive" and below 3 as "Negative".

**`Description:`** A web-based sentiment analysis tool using Python and Flask to classify restaurant reviews. It compares Naive Bayes, SVM, and LSTM models to select the best performer for analyzing user-input text and displaying sentiment results with visuals.

**`Results:`** 
- Achieved accurate sentiment classification, with SVM delivering the best performance, followed by LSTM, and Naive Bayes.

- Successfully built a functional local web application that allows users to input text and receive real-time sentiment predictions.

- Enhanced user interaction with visual feedback tied to sentiment outcomes (Positive/Negative).

### SQL

#### **📌Warehouse Management System – Electronics Distribution Company**

**`Link:`** [Warehouse Management System – Electronics Distribution Company](https://github.com/LamVKiet/WAREHOUSE-MANAGEMENT-SYSTEM/tree/main)

**`Goal:`** To build a relational database system that efficiently manages warehouse operations and ensures data integrity.

**`Description:`** This database system is designed to support the warehouse operations of an electronics distribution company. It manages the processes of importing and exporting goods, as well as tracking suppliers, customers, inventory, employees, and job roles.

**`Results:`**
- Designed and developed a complete relational database system with a clear ERD diagram and a schema normalized to 3NF to efficiently manage warehouse operations.

- Integrated data integrity constraints and triggers to minimize input errors and ensure data consistency and reliability throughout the operational workflow.

- Enabled easy querying of supplier, customer, and employee data to support decision-making and facilitate accurate reporting.

#### **📌Profitability Diagnostics & Loss Root Cause Analysis Using Advanced SQL**

**`Link:`** [Profitability Diagnostics & Loss Root Cause Analysis Using Advanced SQL](https://github.com/LamVKiet/Profitability-Diagnostics-Loss-Root-Cause-Analysis-Using-Advanced-SQL)

**`Goal:`** Use SQL to analyze profitability, identify loss drivers, and provide actionable insights to enhance business performance.

**`Description:`** This project utilizes SQL for root cause analysis, allowing the identification of underperforming products, high-risk customers, and unprofitable regions through drill-down queries. By leveraging advanced SQL techniques such as Subqueries, Window Functions, CTEs, Grouping & Aggregation, CASE Statements, and Stored Procedures, it offers a data-driven approach to enhance decision-making and drive profitability improvements.

**`Results:`** 

This project delivers actionable insights to enhance business performance through advanced data analysis. Key focus areas include:

- Product Portfolio Optimization – Identifies low-performing products to reallocate resources toward better-performing, more profitable items, helping improve overall profitability and streamline inventory.

- Customer Segmentation Insights – Analyzes customer groups to refine segmentation, enhance targeting and increase retention.

- Geographic Profitability Focus – Pinpoints underperforming regions to guide localized strategies in logistics, marketing, and resource allocation for better regional performance.

- Discount Strategy Optimization – Evaluates the effectiveness of discounting practices to reduce revenue leakage and improve promotion outcomes.

- Loss Driver Identification – Detects key loss areas across products, customers, and regions, enabling timely, data-driven corrective actions to boost profitability.
### PowerBI

#### **📌Store Sales Dashboard**

**`File:`** [PowerBI - Store Sales Dashboard](https://github.com/LamVKiet/Dashboard)

**`Description:`** This dashboard visualizes key sales data, including monthly and daily revenue trends, payment methods, and sales types. It also highlights sales performance across different product categories, product id, providing a clear view of business trends.

### Excel

#### **📌Product Dashboard**

**`Files:`** [Excel - Product Dashboard](https://github.com/LamVKiet/Dashboard)

**`Description:`** This dashboard visualizes sales data, showcasing the quantity of products sold by category and product ID. It includes insights into sales trends across different time periods (yearly, monthly, daily), as well as the buying and selling prices for each category and product.

## Education

University of Economics Ho Chi Minh City: Bachelor’s Degree, Data Science, 2022 – 2025


## Contact
I’m happy to connect regarding career opportunities, collaborations, or feedback. 
- **Email** l.vikiet21@gmail.com 
- **Linkedin**: [@kietlam](http://linkedin.com/in/kiet-lam-312052310)

