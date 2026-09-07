# Avinash Narayan | Data Analyst Internship Portfolio

## ApexPlanet Data Analyst Internship

This is my master portfolio for the ApexPlanet Data Analyst Internship. It brings together five stages of an end-to-end analytics workflow: data cleaning, exploratory analysis, SQL/business analysis, interactive dashboarding, statistical validation, data storytelling, and portfolio integration.

## Internship Journey

| Task | Focus | Key Skills |
|---|---|---|
| Task 1 | Data Immersion & Wrangling | Data cleaning, data quality checks, Excel, Python |
| Task 2 | Exploratory Data Analysis & Business Intelligence | EDA, SQL, Excel dashboarding, business insights |
| Task 3 | Deep-Dive Analysis & Interactive Dashboarding | Power BI, DAX, KPI design, customer segmentation |
| Task 4 | Data Storytelling & Statistical Validation | Business storytelling, hypothesis testing, Welch's t-test |
| Task 5 | Capstone Integration & Portfolio Finalization | Portfolio development, documentation, presentation |

## Project Overview

The project uses a sales transaction dataset containing order, customer, demographic, product, category, quantity, pricing, city, and sales information.

The overall workflow was:

**Raw Data → Cleaning → EDA → SQL Analysis → KPI Dashboard → Customer Segmentation → Statistical Validation → Business Recommendations → Portfolio**

## Task 1 — Data Immersion & Wrangling

I profiled and cleaned the sales dataset, checked data quality, handled missing values and inconsistencies, standardized dates, checked duplicates, and produced an analysis-ready dataset.

**Repository:**  
https://github.com/TechyLearner/Task-1-ApexPlanet-Internship

## Task 2 — Exploratory Data Analysis & Business Intelligence

I used Excel and MySQL to explore sales performance across categories, products, cities, customers, gender, and time, and created a static dashboard.

Key findings included approximately ₹139.40 million in total sales, approximately 1,000 orders, and approximately ₹139,399 average order value. Electronics was the leading sales category.

**Repository:**  
https://github.com/TechyLearner/Task-2---Apex-Planet-Internship

## Task 3 — Deep-Dive Analysis & Interactive Dashboarding

I built my first interactive Power BI dashboard with five core KPIs:

- Total Sales
- Total Orders
- Average Order Value
- Total Quantity
- Unique Customers

The deep-dive focused on High Value, Medium Value, and Low Value customer segmentation using percentile-based business rules, with interactive filters for city, segment, product, and gender.

**Repository:**  
https://github.com/TechyLearner/Task-3-Apex-Planet-Internship

## Task 4 — Data Storytelling & Statistical Validation

I combined the previous findings into a business narrative and tested:

**Do High Value customers generate significantly higher average order values than Low Value customers?**

A Welch independent two-sample t-test was applied to customer-level AOV.

Key result:

- High Value customer AOV: approximately ₹314,483.88
- Low Value customer AOV: approximately ₹18,742.07
- Mean difference: approximately ₹295,741.81
- p-value: 5.706 × 10⁻¹¹³
- Cohen's d: approximately 5.10

The null hypothesis was rejected at α = 0.05, providing very strong evidence that High Value customers have substantially higher customer-level AOV.

**Repository:**  
https://github.com/TechyLearner/Task-4-ApexPlanet-Internship

## Final Presentation

The final refined presentation is included in this repository:

`Task_5_Final_Portfolio_Presentation.pptx`

## Key Learnings

### Technical Skills

- Microsoft Excel
- Python
- MySQL
- Power BI
- DAX
- Statistical hypothesis testing
- Data visualization
- GitHub and repository management

### Analytical Skills

- Data cleaning and quality assessment
- Exploratory data analysis
- Business question formulation
- KPI development
- Customer segmentation
- Trend and category analysis
- Statistical validation
- Business recommendation development

### Communication Skills

- Data storytelling
- Business-focused presentation
- Dashboard walkthroughs
- Stakeholder-oriented communication
- Technical documentation

## Business Impact

The project demonstrated how transactional data can be transformed into actionable business insight.

The analysis identified important revenue drivers, customer segments, sales patterns, and a statistically validated difference in customer-level order value.

The main recommendations were to prioritize High Value customer retention, develop Medium Value customers through targeted engagement, selectively activate Low Value customers, and continuously monitor performance through the dashboard.

## Tools & Technologies

**Data Preparation:** Excel, Python  
**Database & Querying:** MySQL  
**Business Intelligence:** Power BI, DAX  
**Statistics:** Welch's independent two-sample t-test, Mann–Whitney U test  
**Documentation & Presentation:** Microsoft Word, Microsoft PowerPoint  
**Portfolio:** GitHub, LinkedIn

## Final Reflection

This internship gave me practical experience across the complete data analytics lifecycle.

My biggest takeaway was learning that data analysis is not only about calculations and charts. It is about asking useful business questions, validating findings, communicating them clearly, and turning evidence into decisions.

## Author

**Avinash Narayan**

Aspiring Data Analyst

GitHub: https://github.com/TechyLearner  
Portfolio: https://final-dev-portfolio-sepia.vercel.app/

## Acknowledgement

I would like to thank ApexPlanet Software Pvt. Ltd. for providing the opportunity to complete this Data Analyst Internship and gain practical experience across the data analytics lifecycle.
