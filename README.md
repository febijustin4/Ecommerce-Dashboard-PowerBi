# Ecommerce Performance Dashboard

A comprehensive Power BI dashboard project designed to analyze and track ecommerce business performance across sales, customers, and delivery operations

---

## Project Overview

This project provides a complete view of an ecommerce business by combining multiple datasets and creating interactive dashboards to monitor:

Sales performance
Customer behavior
Delivery efficiency

The goal is to help stakeholders make data-driven decisions using clear visual insights.

## Key Features
📈 Sales performance tracking

👥 Customer insights and behavior analysis

🚚 Delivery and order status monitoring

📊 Interactive dashboards with filters and slicers

📅 Month-over-Month (MoM) growth analysis

# Dashboard Modules 

## Sales Dashboard

Total Sales

Total Orders

Average Order Value (AOV)

Monthly Sales Trends

MoM Growth %

## Delivery Dashboard

Delivered Orders

Cancelled Orders

Cancellation Rate

Average Delivery Time


## Customer Dashboard

Total Customers

Repeat Customers

Orders per Customer

Customer Lifetime Value (CLV)

## Tools & Technologies

Power BI

DAX (Data Analysis Expressions)

Excel (Data Source)

## Sample DAX Measures

Total Sales = SUMX(Sales, Sales[Quantity] * Sales[Unit Price])


AOV = DIVIDE([Total Sales], [Total Orders])


MoM Growth % =
DIVIDE(
    [Total Sales] - [Previous Month Sales],
    [Previous Month Sales]
)


## Project Workflow

Data collection from Excel

Data cleaning and transformation

Data modeling in Power BI

Creating DAX measures

Building interactive dashboards

## Key Insights

Identified top-performing products and categories

Analyzed repeat customer behavior

Detected cancellation trends in delivery

Improved understanding of monthly sales growth

## Project Output

### Sales Dashboard

<img width="1180" height="652" alt="Sales Dashboard" src="https://github.com/user-attachments/assets/28c932a1-b425-4491-b32c-792ae9eb92d5" />


### Delivery Dashboard

<img width="1176" height="651" alt="Delivery Dashboard" src="https://github.com/user-attachments/assets/f9c5295f-bdf3-4013-a388-801c6f74a638" />


### Customer Dashboard

<img width="1178" height="657" alt="Customer Dashboard" src="https://github.com/user-attachments/assets/884033a9-3016-432f-8026-dbd25e0843ba" />





 
