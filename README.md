# Business Insights 360
This is a Data Analytics project I have done using Power BI

# Project Overview
AtliQ Hardware is growing rapidly in the recent years, and they have decided to implement the data analytics using PowerBi in their company for the first time to surpass their competitors in the market and to make data driven decisions. This project is hoped to give answers to the questions of stakeholder in terms all the aspects like finance, sales, marketing and supply chain.

I worked on this project by following the Codebasics PowerBi Course, Link to the course is [here](https://codebasics.io/courses/power-bi-data-analysis-with-end-to-end-project)

[Live Dashboard Link](https://www.novypro.com/project/business-insights-360-43)

# Tech stacks
* SQL
* PowerBi Desktop
* Excel
* DAX language
* DAX studio (for optimizing the report)

# PowerBI techniques taken
* What are all the questions should be asked before staring the project
* Creating calculated columns
* creating measure using DAX language
* Data modeling
* Using Bookmarks to switch between two visuals
* Page navigation with buttons
* Using divide function to prevent zero division errors
* creating date table using m language
* Dynamic titles based on the applied filters
* Using KPI indicators
* Conditional formatting the values in visuals using icons or background color
* Data validation techniques
* PowerBi services
* Publishing reports to PowerBi services
* Setting up personal gateway to set up the auto refresh of data
* PowerBi App creation
* Collaboration, workspace, access permissions in PowerBi services

# Business related terms
* Gross price
* Pre-invoice deductions
* Post-Invoice deductions
* Net Invoice sales
* Gross Margin
* Net sales
* Net profit
* COGS - cost of goods sold
* YTD - Year to Date
* YTG - Year to Go

# Company’s back ground
AltiQ hardware is a company which has grown vastly in the recent years, and opened business all over the globe. It is a company which sells, computer and computer accessories through three mediums/channel

* Retailers
* Direct
* Distributors

Recently the company has faced a unforeseen loss by opening store in America based on the surveys, intuition and some excel analysis and also the company’s competitors has handful of analytics team to perform analysis and make data driven decision. So, the AltiQ hardware has no other option other than building their analytics team for data driven insights and decisions in the future to survive better in the industry.

# Questions to ask before starting with dashboard
* What is the objective of building this PowerBi dashboard?
* In what terms the success of this project will be measured?
* What will be time dead-line of the project?
* Do the stakeholders expecting pre-view before the actual release?
* What are all the hopes stakeholders have out of this project?
* what are all fears the stakeholder have in terms of building this dashboard?
* Who are all will be using this dashboard and for what purpose?
* what are all expectation the stakeholders have, by the completion of this project?
* What can go wrong while building this project?
* what are all the resources/ data needed to build this dashboard?
* Is there any inputs from stakeholders in terms of design and views of the dashboard?

After the project kick off meetings, the data engineering team has given the data as per the request of data analytics team, let’s explore them.

# Dataset Understanding.
Understanding what data is available will be more helpful while doing analysis. before jumping on to the analysis get good understanding of what are data available.

Dimension table : It will have the static data like details of customer and products

Fact table : It will have the data about the transactions

* gdb041:
- dim_customer
- dim_market
- dim_product
- fact_forecast_monthly
- fact_sales_monthly

* gdb056:
  
- freight_cost
- gross_price
- manufacturing_cost
- Pre_invoice_dedutions
- Post_invoice_deductions

# Importing data into PowerBi
As the database is MySQL in this project, we need to import the datasets from Mysql database to PowerBi by providing the Database access credential

# Data Model
* Data modeling plays a vital role and is considered as the basement of report. All the visuals will be build upon the data model.
* Poor data modeling affects the over all performance of the report.
* Following Good practices of data modeling is must. Refer this page to get to know the good practices Blog
* In this project, we have followed Snowfall data modeling method.
<img width="838" alt="Data_model" src="https://github.com/KarthikSooraj/Business-Insights-360/assets/141903858/7085c718-1296-4a81-a1d7-309de3480d9c">

# Dashboard designing
Based on the mock ups received as requirement, the team will start designing the visuals and create measure as and when required.

# Home view
In Home view, all the views button will be available. User will land on specific view page by clicking the button

- Info
- Finance View
- Sales View
- Marketing View
- Supply chain View
- Executive View
- Products
- Support

# Project Outcome
By using this report, decisions can be taken based on the data. Further it will help in answering many questions based on the situations.
