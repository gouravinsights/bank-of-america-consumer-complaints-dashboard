# 📊 Bank of America Consumer Complaints Dashboard

An interactive Power BI dashboard built using the **Consumer Financial Protection Bureau (CFPB) Consumer Complaint Database**, analyzing **50,000+ consumer complaints** related to Bank of America between **2017 and 2023**.

The project focuses on identifying complaint trends, customer issues, company response performance, product-wise analysis, and executive-level business insights.

---

# Dashboard Preview

## Executive Summary

![Executive Summary](Images/BOA%201.png)

---

## Product Analysis

![Product Analysis](Images/BOA%202.png)

---

## Response & Operational Analysis

![Response Analysis](Images/boa%203.png)

---

# Project Objectives

The dashboard was designed to answer the following business questions:

- How many complaints were received?
- Which financial products generate the highest number of complaints?
- Which complaint issues occur most frequently?
- Which states report the highest complaint volumes?
- Which submission channels are used the most?
- What percentage of complaints receive timely responses?
- How long does the company take to respond?
- How does complaint volume change over time?
- How do complaint patterns differ across products and sub-products?
- How does Bank of America's response vary by complaint type?

---

# Dashboard Pages

## 1. Executive Summary

Provides a high-level overview of complaint activity including:

- Total Complaints
- Products Covered
- Complaint Categories
- States
- Timely Response %
- Average Response Time
- Monthly Complaint Trend
- Product-wise Complaint Distribution
- Complaint Submission Channels
- Top States by Complaint Volume

---

## 2. Product Analysis

Detailed analysis of financial products including:

- Complaint trends over time
- Top complaint issues
- Company responses
- Top sub-products
- Product vs Issue Treemap

---

## 3. Response & Operational Analysis

Operational performance dashboard focusing on:

- Timely Response Rate
- Average Days to Respond
- Company Response Distribution
- Complaint Submission Channels
- Product-wise Response Time
- Response Trends Over Time

---

# Dataset

Source:

**Consumer Financial Protection Bureau (CFPB)**

https://www.consumerfinance.gov/data-research/consumer-complaints/

Dataset Used:

Consumer Complaint Database (Filtered for Bank of America)

Time Period:

**2017 – 2023**

---

# Tools Used

- Power BI Desktop
- Power Query
- DAX
- Data Modeling
- Interactive Visualizations

---

# Data Model

Star Schema

- Date Dimension
- Consumer Complaints Fact Table

Relationship:

```
Date (1)
      │
      │
Consumer Complaints (*)
```

---

# DAX Measures Created

Some of the measures used include:

- Total Complaints
- Total Products
- Total Issues
- Total States
- Timely Responses
- Timely Response %
- Average Days to Company

Custom Date Table including:

- Year
- Quarter
- Month
- Month Number
- Day Name
- Day Number
- Year-Month
- Year-Quarter

---

# Key Insights

- Over **50,000** complaints were analyzed.
- Complaint volume peaks during mid-year.
- Checking/Savings Accounts generate the highest complaint volume.
- California reports the highest number of complaints.
- More than **95%** of complaints receive a timely response.
- Most complaints are submitted through the Web portal.
- Average response time is approximately **1 day**.

---

# Repository Structure

```
bank-of-america-consumer-complaints-dashboard
│
├── Dashboard
│     └── BANK OF AMERICA.pbix
│
├── Data
│     └── Dataset (if shareable)
│
├── Images
│     ├── BOA 1.png
│     ├── BOA 2.png
│     └── boa 3.png
│
└── README.md
```

---

# Skills Demonstrated

- Data Cleaning
- Data Modeling
- Star Schema Design
- DAX
- Time Intelligence
- KPI Development
- Dashboard Design
- Business Intelligence
- Storytelling with Data
- Interactive Reporting

---

# Author

**Gourav Dutta**

LinkedIn: *(Add your LinkedIn URL)*

GitHub: https://github.com/gouravinsights

---
