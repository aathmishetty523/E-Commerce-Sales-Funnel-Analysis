Olist End-to-End E-Commerce & Marketing Analytics


An end-to-end analytics project built on the Olist Brazilian E-Commerce and Marketing Funnel datasets, covering the complete workflow from raw data ingestion -> analytical modeling -> SQL insights -> Power BI dashboards.

This project demonstrates how real-world analytics teams design data models, validate data, derive insights, and communicate results through interactive dashboards.

Business Context & Objectives


Olist is a Brazilian e-commerce platform connecting sellers and customers across multiple categories.



The objective of this project is to analyze:



Overall e-commerce performance
Customer and seller behavior
Product and category trends
Order fulfillment and delivery performance
Marketing funnel effectiveness (MQL -> closed sellers)
Revenue quality of acquired sellers
The project is structured to reflect how analytics work is performed in production environments.

Dataset Overview


This project uses publicly available datasets from Kaggle, spanning two analytical domains:

Transactional E-Commerce Data
CRM-Style Marketing Funnel Data
Detailed dataset descriptions and source links are documented in: -> 02_data_sources/

Domains Covered


E-Commerce Transactions

Customers
Orders
Sellers
Products
Categories
Payments
Reviews
Marketing Funnel

Marketing Qualified Leads (MQLs)


Closed Deals (seller acquisition outcomes)
The dataset intentionally combines transactional e-commerce data with CRM-style marketing funnel data, enabling both operational analytics and growth-focused funnel analysis.

Project Architecture
The repository is organized to mirror a real-world analytics workflow:

01_project_overview
Business context, problem framing, and analytical objectives

02_data_sources
Dataset scope, source tables, and data lineage documentation

03_ddl_table_creation
Staging and analytical table definitions (schema design)

04_dml_data_load
Data ingestion and controlled transformation logic

05_data_validation
Data quality checks, integrity validation, and sanity tests

06_star_schema
Analytical data models

Star schema for e-commerce transactions
Funnel-based logical model for marketing data
07_Analytical_Insights
SQL-driven business analysis and metric derivation

08_power_bi_dashboard
Interactive Power BI dashboards and supporting screenshots

Each folder represents a logical stage in the analytics lifecycle, from raw data to final insights.

