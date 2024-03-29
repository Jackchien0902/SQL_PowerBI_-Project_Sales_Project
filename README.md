# SQL_PowerBI_-Project_Sales_Project
1）Business Request

Steven - Sales Manager:

Hi，

I hope you are doing well. We need to improve our internet sales reports and want to move from static reports to visual dashboards. Essentially, we want to focus it on how much we have sold of what products, to which clients and how it has been over time. Seeing as each sales person works on different products and customers it would be beneficial to be able to filter them also. We measure our numbers against budget so I added that in a spreadsheet so we can compare our values against performance. The budget is for 2024 and we usually look 2 years back in time when we do analysis of sales. Let me know if you need anything else!

// Steven

2）Business Demand Overview

Reporter: Steven – Sales Manager
Value of Change: Visual dashboards and improved Sales reporting or follow up or sales force
Necessary Systems: Power BI, CRM System
Other Relevant Info: Budgets have been delivered in Excel for 2024
3）User Stories:


| No # | As a (role)          | I want (request / demand)         | So that I (user value)                               | Acceptance Criteria                                      |
| ---  | -------------------  | -------------------------------   | ---------------------------------------------------   | ------------------------------------------------------- |
| 1    | Sales Manager        | Get a dashboard overview of internet sales | Follow sales trends for customers and products that perform the best | Power BI dashboard with daily data updates             |
| 2    | Sales Representative | View detailed Internet Sales per Customers | Identify top customers and opportunities for upselling | Power BI dashboard with customer-specific filters       |
| 3    | Sales Representative | View detailed Internet Sales per Products  | Identify top-selling products                        | Power BI dashboard with product-specific filters        |
| 4    | Sales Manager        | Access a dashboard of internet sales | Track sales performance against budget                | Power BI dashboard with graphs and KPIs comparing to budget |

**4）Technologies:**

SQL Server, SQL Server Managemet Studio and Power Bi

5）Dataset:

https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksDW2022.bak

https://github.com/Microsoft/sql-server-samples/releases/download/adventureworks/AdventureWorksLT2022.bak

https://github.com/techtalkcorner/SampleDemoFiles/blob/master/Database/AdventureWorks/Update_AdventureWorksDW_Data.sql

https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/blob/main/Sales%20Budget.xlsx 

**6）Task Breakdown**

[Task 1 Data Clean & Transformation](https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/blob/main/Data%20Cleaning)

Task 2 Create Dashboard

1.Data Model

Below is a screenshot of the data model after cleansed and prepared tables were read into Power BI.

This data model also shows how FACT_Budget has been connected to FACT_InternetSales and other necessary DIM tables.

![image](https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/assets/157054789/0f02a909-07e8-4981-9633-3b5a45467b7a)


2.Sales Management Dashboard

The finished sales management dashboard with one page with works as a dashboard and overview, with two other pages focused on combining tables for necessary details and visualizations to show sales over time, per customers and per products.

https://app.powerbi.com/view?r=eyJrIjoiZTZjM2VlZTktZGZkNi00ZjlhLWJkYjEtNGE0OWM4MThmNjZiIiwidCI6ImVlNmNiZGYzLTkyM2EtNGYzMi1hMzYyLTJjNDlkOTU5OTQ5ZiJ9

![Customer Details](https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/assets/157054789/816dc69f-301b-4e26-a115-b2defb813512)
![Product Details](https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/assets/157054789/97a7f321-40f6-4277-8ea0-e19edf1f75bd)
![Sales Overview](https://github.com/Jackchien0902/SQL_PowerBI_-Project_Sales_Project/assets/157054789/f1779897-e18c-4418-b0b6-9fc64a471a3a)
