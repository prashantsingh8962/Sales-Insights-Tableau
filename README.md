# Sales-Insights-Tableau

## Project Overview
AtliQ Hardware has experienced significant growth in recent years and has decided to implement data analytics using Tableau for the first time. The goal is to leverage data-driven insights to outperform competitors and support decision-making across various aspects of the business, including finance, sales, marketing, and supply chain management.

[Data Analytics Bootcamp 3.0: With Practical Job Assistance + AI Module](https://codebasics.io/#ourcourses)

This project is designed to provide actionable insights to stakeholders, enabling them to make informed decisions that will drive the company's continued success.

## Tech Stacks
- SQL
- Tableau Desktop
- Excel
- Calculated Fields
- Data Modeling
- Tableau Prep (for data preparation)

## Tableau Techniques Learned
- Key questions to ask before starting a dashboard project
- Creating calculated fields
- Using parameters for dynamic filtering and interaction
- Data modeling and relationships
- Bookmarking and navigating between different visualizations
- Avoiding zero-division errors using the `DIVIDE()` function
- Creating custom date tables using calculated fields
- Designing dynamic titles based on filters applied
- Implementing KPIs and conditional formatting
- Data validation and accuracy checks
- Publishing and managing Tableau dashboards on Tableau Server or Tableau Public
- Setting up scheduled data refreshes
- Collaboration and access management in Tableau Server
- And more...

## Project Charter
This project follows a structured approach, beginning with a project kickoff session to clarify objectives, success criteria, timelines, stakeholder expectations, and potential risks. The data engineering team provided the necessary datasets, and the analytics team used Tableau to build dashboards that offer comprehensive business insights.

## Dataset Understanding
Understanding the available data is crucial for effective analysis. Here’s a breakdown of the dataset used in this project:

- **Dimension Tables**: Contain static data such as customer and product details.
- **Fact Tables**: Contain transactional data.

### Key Tables:
- `dim_customer`: 27 distinct markets, 75 customers, 2 sales platforms (Brick & Mortar, E-commerce)
- `dim_market`: 27 markets, 7 sub-zones, 4 regions (APAC, EU, NA, LATAM)
- `dim_product`: Different divisions like Peripherals, Accessories, Networking
- `fact_forecast_monthly`: Used for customer demand forecasting
- `fact_sales_monthly`: Tracks actual sales data
- `freight_cost`: Contains travel and other logistical costs
- `gross_price`: Product pricing details
- `manufacturing_cost`: Manufacturing cost details
- `pre_invoice_deductions`: Pre-invoice deductions percentages
- `post_invoice_deductions`: Post-invoice deductions and adjustments

## Data Modeling
Data modeling is the foundation of the Tableau report. A well-structured data model enhances the performance and accuracy of the dashboard. This project follows best practices in data modeling, utilizing a snowflake schema.

<img src="https://github.com/prashantsingh8962/Sales-Insights-Tableau/blob/main/Resources/Data%20Model%20tableau.png" class="center">

## Dashboard Design
The dashboard design is based on mockups received from stakeholders. Each view serves a specific business function:

- **Revenue-Sales View**: Sales trends and performance
- **Profit View**: Marketing effectiveness


## Project Outcome
This Tableau report enables data-driven decision-making, helping to address various business challenges and opportunities. Stakeholders can use this report to answer critical business questions and drive future growth.

## Report Links
- [Live Dashboard Link](https://github.com/prashantsingh8962/Sales-Insights-Tableau/blob/main/Report/My%20Sales%20Insights.twb)


This README provides a clear and comprehensive overview of the Tableau project, emphasizing the tools, techniques, and outcomes. It’s designed to be informative for anyone looking to understand the project's scope and implementation.
