🦄 Unicorn Companies SQL Data Analysis Project

📌 Project Overview

This project performs exploratory and business-focused analysis on a Unicorn Companies dataset using SQL. Unicorn companies are privately held startups valued at over $1 billion. The project involves designing a relational database, creating normalized tables, and executing advanced SQL queries to uncover trends related to valuation, funding, industries, investors, geographic distribution, and growth patterns.

The analysis provides insights into how unicorn companies are distributed across continents and industries, which sectors attract the most investment, and how quickly startups achieve unicorn status.

🎯 Objectives

Design a normalized SQL database for unicorn company analysis.
Explore valuation and funding trends across industries.
Analyze geographic distribution of unicorn companies.
Identify high-growth startups and investment patterns.
Perform business intelligence reporting using SQL.
Generate actionable insights from startup ecosystem data.

🗄 Database Schema

The project uses four normalized tables:

Companies Table

Stores company and location information.

Company ID
Company Name
City
Country
Continent
Dates Table

Stores founding and unicorn joining dates.

Company ID
Date Joined
Year Founded
Funding Table

Stores financial information.

Company ID
Valuation
Funding Amount
Selective Investors
Industries Table

Stores industry classification.

Company ID
Industry

The tables are connected through primary and foreign key relationships using company_id.

🛠 Technologies Used

Database
MySQL
SQL Concepts
Database Design
Primary & Foreign Keys
Joins
Aggregate Functions
Subqueries
Group By
Order By
Data Filtering
Business Analytics Queries

🔍 Key SQL Analysis Performed

1. Top 5 Most Valuable Unicorn Companies

Identified the highest-valued unicorn companies based on valuation.

2. Unicorn Distribution by Continent

Analyzed the number of unicorn companies present across continents.

3. Legacy Startups Becoming Unicorns

Found companies founded before 2000 that achieved unicorn status after 2015.

4. Industry-Wise Average Valuation

Calculated average company valuation across industries.

5. Companies with the Most Investors

Identified unicorns attracting the highest number of investors.

6. Funding-to-Valuation Analysis

Measured how efficiently companies converted funding into valuation growth.

7. Most Common Industry by Continent

Examined dominant industries across different continents.

8. Above-Average Funded Companies

Identified companies that raised more funding than their industry average.

9. Fastest-Growing Unicorns

Calculated the shortest time taken by startups to achieve unicorn status.

10. Oldest Unicorn Companies

Analyzed long-standing startups that remain unicorns today.

11. Average Years to Unicorn Status by Continent

Compared startup growth speed across continents.

12. Most Common Founding Years

Studied startup formation trends among unicorn companies.

13. High-Valuation Legacy Startups

Found companies founded before 2010 with valuations exceeding $10 billion.

14. Continent with Highest Total Valuation

Determined which continent contributes the greatest total unicorn valuation.

15. Industries with Highest Average Funding

Identified industries receiving the largest investments.

16. Industry Diversity by Country

Measured innovation diversity by counting industries represented within each country.

17. Countries Producing Recent Unicorns

Analyzed countries with the highest number of unicorns created after 2022.

📊 Business Insights Generated

Geographic hotspots for unicorn creation.
Industry sectors attracting the highest investments.
Startup growth trends across continents.
Funding efficiency analysis.
Investor participation patterns.
Emerging countries and industries in the unicorn ecosystem.

📁 Project Structure

Unicorn-SQL-Analysis/
│
├── dataset/
│   └── unicorn_companies.csv
│
├── sql/
│   └── Unicorn_Project.sql
│
├── schema/
│   └── database_schema.sql
│
├── screenshots/
│   ├── top_valuations.png
│   ├── continent_analysis.png
│   ├── industry_analysis.png
│   └── funding_analysis.png
│
└── README.md

📈 Skills Demonstrated

SQL Query Writing
Relational Database Design
Data Modeling
Business Intelligence
Data Analysis
Aggregation & Reporting
Advanced Joins
Subqueries
Analytical Thinking

👨‍💻 Author

Abhishek Singh

M.Sc. Statistics
Banaras Hindu University (BHU)

