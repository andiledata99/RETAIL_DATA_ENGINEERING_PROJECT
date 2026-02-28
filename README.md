# RETAIL_DATA_ENGINEERING_PROJECT

This project implements a complete enterprise-grade retail data platform using SQL Server and SSIS, designed to simulate real-world data engineering practices. The solution focuses on building a secure, automated, and analytics-ready pipeline for retail sales transactions.

# Objectives

• 	Design and deploy a two-tier database architecture:
• 	RetailStaging for raw data ingestion
• 	RetailDataWarehouse for analytics and reporting
• 	Automate ETL processes with SSIS packages to handle 12 monthly CSV files (1.2 million records total).
• 	Implement role-based access control (RBAC) to ensure secure data usage.
• 	Deliver analytical views that provide actionable business insights.

# Architecture

• 	RetailStaging Database: Raw ingestion layer with no transformations.
• 	RetailDataWarehouse Database: Star Schema design with dimension tables (Product, Store, Cashier, Date) and a central FactSales table.
• 	ETL Automation: SSIS packages load, transform, and populate warehouse tables with error handling and logging.

# Security

• 	StoreManager: Full control, including SSIS execution.
• 	DataAnalyst: Read-only access to warehouse, can create views.
• 	CashierUser: Restricted to reporting views only.

# Analytical Views

The project delivers key business reporting views:
• 	Daily sales trends ()
• 	Store performance analysis ()
• 	Category-level revenue ()
• 	Top 10 products ()
• 	Cashier performance ()
• 	Province-level revenue ()
• 	Monthly sales summaries ()


# Deliverables

• 	SQL scripts for database setup
• 	SSIS packages for ETL automation
• 	Completed analytical views
• 	Documentation and final presentation/demo  

# Learning Outcomes

Participants gain hands-on experience in:
• 	Enterprise database architecture
• 	Dimensional modeling (Star Schema)
• 	SSIS automation and error handling
• 	SQL Server security implementation
• 	Retail analytics and reporting

# Real-World Application in Retail Businesses

This project mirrors the challenges and opportunities faced by modern retail enterprises. In the real market, retailers generate massive volumes of transactional data daily—from point-of-sale systems, online platforms, and customer loyalty programs. Without a structured pipeline, this data often remains siloed, inconsistent, and underutilized.

By implementing a staging-to-warehouse architecture, retailers can:
• 	Centralize and standardize data: Ensures all sales transactions are captured consistently across stores and channels.
• 	Enable accurate reporting: Analytical views like daily sales, store performance, and category revenue provide managers with real-time visibility into operations.
• 	Support decision-making: Insights into top-performing products, cashier efficiency, and regional revenue trends help optimize staffing, inventory, and marketing strategies.
• 	Enhance security and governance: Role-based access control ensures sensitive data is protected while empowering analysts and managers with the right level of access.
• 	Drive growth and competitiveness: With automated ETL and scalable warehouse design, businesses can quickly adapt to seasonal changes, promotions, and customer behavior shifts.
In essence, this project demonstrates how data engineering transforms raw transactions into actionable intelligence. For retail businesses, such a system is not just important—it is critical for survival in a competitive market where margins are tight, customer expectations are high, and data-driven agility defines success.


