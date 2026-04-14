This project presents a Power BI dashboard built using an AI-generated pharmacy sales dataset simulating the Indian healthcare market. It analyzes sales, profit, discounts, product categories, and regional trends to demonstrate data cleaning, modeling, and business insight generation for portfolio and interview use.


🏥 Pharmacy Sales Analytics Dashboard (India)
📌 Project Overview
This project showcases an end-to-end analytics workflow using a synthetic pharmacy sales dataset representing transaction-level sales in the Indian healthcare market.
The objective is to demonstrate data engineering, data cleaning, Power BI modeling, and dashboard design skills through a single, well-structured portfolio project.
The final output is an interactive one-page Power BI dashboard suitable for executive reporting, business analysis, and interview demonstrations.
📊 Dataset Description
The dataset simulates realistic pharmacy sales behavior across:
Indian pharmaceutical brands
Dosage categories and sub-categories
Discount strategies
Cities and regions in India
Time (monthly and yearly trends)
It contains 2,000 records with financial, product, geographic, and time attributes, enabling comprehensive analysis of:
Sales performance
Profitability
Discount impact
Regional and city-level trends
🔹 Note
This dataset is synthetic and created purely for educational and portfolio purposes.
The prompt used to generate this dataset has been uploaded to the repository to ensure transparency and reproducibility.
🏗️ Dataset Creation Process
The dataset was programmatically generated with the following considerations:
6–8 popular Indian pharmaceutical brands
Dosage-based product categories:
Orals, Parenteral, Topical, Inhalation, Rectal, Vaginal, Nasal, Otic, Transdermal
Logical Category → Sub-Category mapping
Discount bands:
High, Medium, Low, None
8 Indian cities, mapped correctly to 4 regions:
North, South, East, West
Realistic sales, cost, and profit calculations
Transaction dates spanning 2022–2024
Business Logic Applied
Gross Sales derived from units sold and pricing assumptions
Discounts applied based on Discount Band
Profit calculated after deducting Manufacturing Cost
🧹 Data Cleaning & Preparation (Power BI)
The following steps were performed in Power BI:
Verified correct data types for numeric, text, and date columns
Created a clean Date column (2022–2024) using DAX for reliable time analysis
Derived Month Name from Date and applied correct month sorting
Created measures instead of calculated columns for dynamic analysis
Validated logical relationships between Category, Sub-Category, City, and Region
Ensured no negative or illogical financial values
🧠 Data Modeling & DAX Measures
Key measures created using DAX:
Total Sales
Total Profit
Gross Sales
Units Sold
Profit Margin % (Profit / Sales)
Time-based aggregations for monthly and yearly trends
All measures respond dynamically to slicers and filters, following Power BI best practices.
📈 Dashboard Design & Visual Selection
A single-page Power BI dashboard was designed to present all key insights without scrolling.
Visuals Included
Executive KPIs
Total Sales
Total Profit
Profit Margin %
Gross Sales
Units Sold
Trends & Performance
Sales & Profit trend over time
Monthly sales pattern
Product & Brand Analysis
Category → Sub-Category sales
Top 5 Brands by Profit
Units Sold by Category
Pricing & Cost Analysis
Discount Band impact on Sales and Profit
Manufacturing Cost vs Profit
Geographic Analysis
Sales by Region
City-wise sales comparison
Region × Category Profit Matrix
Interactive Slicers
Brand
Category
Sub-Category
Discount Band
Region
City
Month / Year
🎯 Key Business Questions Answered
Which pharmaceutical brands generate the highest profit?
How do discount strategies affect profitability?
Which dosage categories drive the most revenue and volume?
How does performance vary by region and city?
What seasonal patterns exist in pharmacy sales?
Which categories have strong sales but weaker margins?
🛠 Tools & Technologies Used
Power BI Desktop – Data modeling, DAX, and dashboarding
Excel – Dataset storage
DAX – Measures and time intelligence
GitHub – Project versioning and portfolio presentation

🚀 Portfolio Value
This project demonstrates:
End-to-end data engineering + BI workflow
Healthcare domain understanding
Clean data modeling and DAX usage
Strong dashboard storytelling
Interview-ready Power BI best practices
⚠️ Disclaimer
This dataset is synthetic and does not represent real pharmaceutical company data.
It is intended solely for learning, analytics practice, and portfolio demonstration.
