# Sales_insights-using-PowerBI
This Power BI Sales Insights Dashboard for AtliQ Hardware helps the Sales Director easily monitor sales trends and performance. It converts raw MySQL data into clear visuals using ETL, DAX measures, and currency conversion. The dashboard reveals key insights on revenue, profit margins, regions, products, and customers for better decisions.
# Problem Statement
AtliQ Hardware is a company that delivers computer hardware and peripherals to clients across multiple branches in India. The Sales Director was struggling to clearly understand business performance, as sales were not meeting expectations and were gradually declining. Regional managers were unable to communicate clear status updates, and interpreting complex Excel sheets made it even harder, leading to frustration and poor decision-making.
# Solution
To address this challenge, the Sales Director decided to build an interactive Power BI Dashboard to convert raw data into meaningful visual representations and enable data-driven decisions. A dedicated data team was hired to collect, clean, transform, and visualize the data.
# AIMS Grid
Using the AIMS Grid project management tool, the team defined the project’s purpose, stakeholders, end results, and success criteria to ensure clarity and alignment throughout the project.
# Steps Followed
1. Understood the AIMS Grid for structured project planning.
2. Retrieved raw data from the database using MySQL.
3. Performed data cleaning in Power Query.
4. Completed the ETL process (Extract, Transform, Load).
5. Created custom DAX measures for relevant KPIs.
6. Performed currency conversion to unify different currency types.
7. Validated, modeled, and visualized the data in Power BI.
# Major Changes & Customizations
1. Solved the ‘(blank)’ product issue by replacing the original products table with a custom table (products Prod280–Prod339) with product types (Own Brand or Distribution).
2. Merged the original and modified sales_transaction tables to include profit margin, cost price, and other required fields.
# Insights
1. Total revenue over 4 years: ₹985M | Profit margin: ₹24.7M (2.5%) | Sales quantity: 2M units.
2. 2020 performance: ₹142M revenue, 350K units sold, ₹2.1M profit.
3. Delhi NCR is the top revenue market (₹520M, 52.8% of total) but only a 2.3% profit margin.
4. Highest profit margin city (2020): Bhubaneshwar at 10.48%.
5. Top profit contributor by market: Mumbai (23.89% of total profit).Lowest profit margin: Bengaluru (-20.8% margin, -0.3% profit contribution).
6. Top customer: Electricalsara Stores (₹413M revenue in 4 years).
7. Top product: Prod318 (₹69M revenue in 4 years).
8. Revenue trend: Sharp decline in June 2020, lowest profit margin in April 2020.
9. Product types: Distribution and Own Brand each generated around ₹494M revenue.
#  Key Learnings
1. Gained experience working with real-world business datasets.
2. Practiced writing advanced analysis queries in MySQL.
3. Learned how to connect databases to Power BI, perform ETL, and handle data cleaning in Power Query.
4. Developed practical skills using DAX for measures and KPIs.
5. Designed impactful visuals and reports to support decision-making.
# Tools Used
MySQL, Power BI, Power Query, DAX, AIMS Grid
# Final Result
A clear, interactive Power BI Dashboard KPI Page that empowers the Sales Director and stakeholders to track key metrics, identify problem areas, and make better business decisions based on real-time data.
<img width="966" height="542" alt="image" src="https://github.com/user-attachments/assets/73d94ff3-7008-476e-9996-c2695915481e" />



