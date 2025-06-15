# Production-and-Inventory-Analysis-Dashboard-using-Power-Bi
📊 Production and Inventory Analysis Dashboard Project

Project Overview

As part of my data analytics and visualization journey, I developed a Production and Inventory Analysis Dashboard to help manufacturing stakeholders identify inefficiencies, track performance trends, and optimize resource planning. Using Power BI for dynamic dashboarding and Python (Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn) for exploratory data analysis (EDA) and preprocessing, this project transforms raw production data into actionable insights.
This interactive reporting solution is tailored for both technical and non-technical audiences—from operations managers to supply chain executives—helping them make data-driven decisions with ease.

🛠️ Tools and Technologies Used
•	Power BI – For interactive dashboards and storytelling
•	Python – For data preprocessing and trend analysis
o	Pandas, NumPy – Data wrangling
o	Matplotlib, Seaborn – Static visualizations during EDA
o	Scikit-learn – Optional modeling or pattern identification
•	Excel / CSV – Source data format (assumed from context)

🔍 Key Business Questions Addressed
1.	What are the monthly and yearly trends in production volume and waste percentage?
2.	Which product categories and locations are contributing most to inventory and waste?
3.	How is on-time production tracking over time?
4.	What are the cost implications of production inefficiencies across assembly units?
5.	How can inventory turnover be improved to align with production rates?

🔄 Methodology
1. Data Collection & Cleaning (Python)
•	Cleaned missing values and standardized date fields.
•	Created calculated columns (e.g., WastePercent, OnTimePercent, etc.).
•	Validated production quantities and costs for anomalies.
2. Exploratory Data Analysis (Python)
•	Investigated production trends, inventory levels, and costs using time-series plots and descriptive statistics.
•	Identified spikes in waste, lag in production, and seasonal trends.
3. Data Modeling (Power BI)
•	Built a star schema connecting dimensions like Date, Product, Location, and WorkOrder.
•	Used DAX to compute KPIs such as:
o	Waste Percent
o	On-Time Production Rate
o	Fiscal YTD Production, Inventory Turnover, etc.
4. Dashboarding (Power BI)
Screens included:
•	Index Page: Simple navigation interface for quick access.
•	Production Overview: Trends, lead times, and performance summary.
•	Category Analysis: Pareto analysis of waste cost by reason and product.
•	Inventory Overview: Inventory quantity, value, and turnover by location.
•	Waste Trend: Time series of waste percentages to pinpoint inefficiencies.

💡 Key Findings and Business Impact
•	📉 Identified a major spike in waste percent (~0.97%) in mid-2013, indicating a need for immediate process quality audits.
•	🧾 Drill-down on waste reasons revealed "Trim length too long" and "Drill size too large" as top waste contributors, costing over $250K each.
•	📦 Inventory held heavily in Subassembly and Miscellaneous Storage, indicating overstocking or bottlenecks.
•	⏱️ Lead time averaged 297 hours, highlighting areas for lean process improvements.
•	🎯 On-Time Production hovered around 41.6%, which is well below optimal, signaling scheduling and process inefficiencies.
These insights offer direct cost-saving and efficiency-improving opportunities for operations and procurement teams.

📌 What This Project Demonstrates
This project reflects my ability to:
•	Translate raw operational data into clear, visual insights
•	Build interactive dashboards that allow stakeholders to self-serve answers
•	Apply data storytelling to support strategic and tactical decision-making
•	Use Python for data cleaning, EDA, and validation
•	Work with production and inventory data to pinpoint inefficiencies and hidden costs
Whether in manufacturing, supply chain, or operations analytics, I’m confident in my ability to create solutions that inform, engage, and drive results.

