ReadMe.md
# PROJECT BLUEPRINT

# Project Title
Driving Revenue Growth in Pharmaceutical Sales: A Data-Driven Decision Intelligence Dashboard

# Business Context
Pharmaceutical companies operate in a highly competitive environment where revenue growth depends on effective product positioning, regional strategy, and sales force productivity. Leadership requires timely, data-driven insights to identify growth opportunities and operational inefficiencies.

# Problem Statement
Despite having detailed transaction-level sales data, stakeholders lack a consolidated view of revenue drivers, regional performance disparities, and sales representative efficiency, limiting their ability to make proactive strategic decisions.

# Business Objective 
Enable pharmaceutical sales leadership to drive sustainable revenue growth by identifying high-impact products, untapped regional opportunities, and sales force efficiency gaps through advanced data analysis and interactive dashboards.

 #Stakeholder Questions This Project Answers
 ## Revenue Optimization
- Which drug categories contribute the most to revenue?
- Are we generating revenue through volume or value?
- Which products should be prioritized for growth?
## Market & Regional Strategy
- Which regions and states are over- or under-performing?
- Where does the company have untapped market potential?
- Are certain drugs region-dependent?
## Sales Force Effectiveness
- Which sales reps generate higher revenue per invoice?
- Are some reps active but inefficient?
- Who should be considered for incentives or training?
## Seasonality & Risk
- Are there seasonal demand patterns?
- When should inventory and staffing be optimized?
- Which months show high volatility?

# Key Success Metrics
- Total Revenue
- Revenue Growth 
- Average Invoice Value
- Revenue per Unit
- Sales Efficiency (Revenue per Invoice)
- High-Growth Product Contribution 

# Data Understanding & Assumptions
## Data Overview
•	Transaction-level pharmaceutical sales data
•	Covers products, regions, hospitals, sales representatives, and payment types
## Key Assumptions
•	Unit price is constant per invoice
•	Each invoice represents one sales interaction
•	Data reflects completed and valid transactions only

# Analytics Approach / Methodology
## Analytics Approach
- Data Ingestion
Raw Excel data loaded into a SQL database for structured querying
- Data Cleaning & Validation
Missing values, duplicates, and data types handled using Python (Pandas)
- Exploratory Analysis
SQL and Python used to identify revenue drivers, regional patterns, and anomalies
##Feature Engineering
- Business metrics such as sales efficiency and growth segmentation created
- Visualization & Decision Support
- Insights translated into an interactive Power BI dashboard for stakeholders

# Expected Insights
The analysis is expected to uncover:
- Key revenue-driving drug categories and products
- Regional performance disparities and untapped markets
- Variations in sales representative efficiency
- Seasonal and temporal demand patterns

# Decision Enablement & Recommendation Framework
Based on analytical findings, the project will support leadership in:
- Prioritizing high-growth products and regions
- Identifying sales force optimization opportunities
- Evaluating pricing and volume trade-offs
- Planning inventory and resource allocation using time-based trends

# Scope, Constraints & Future Enhancements
## Scope & Constraints
- Analysis is limited to available transaction-level sales data
- Profitability insights depend on availability of cost data
- Customer-level behaviour analysis is out of scope
## Future Enhancements
- Integration of cost and margin data for profitability analysis
- Addition of predictive models for demand forecasting
- Automation of dashboard refresh using live database connections

# Tech Stack Used
-	Python: Pandas, NumPy, Matplotlib
- Power BI: Dashboard, DAX
- Excel: Raw data
- GitHub: Version control & portfolio



