Pizza Sales Data Analysis — Jupyter Notebook Project

**Project Overview**
This project analyzes a full year of sales data from a fictitious pizza restaurant. The dataset contains order records, pizza details, pizza categories, pricing, and ingredients. The goal is to explore sales performance, customer ordering behavior, and product trends using Python and Jupyter Notebook.
The analysis was performed by merging multiple datasets and generating business insights from the combined data.

**Dataset Description**
The dataset contains four CSV files:
•	orders.csv — Order date and time information
•	order_details.csv — Items included in each order
•	pizzas.csv — Pizza size and price details
•	pizza_types.csv — Pizza names, categories, and ingredients
A data dictionary was also provided to explain each column.

**Tools Used**
•	Python
•	Jupyter Notebook
•	Pandas
•	Matplotlib
•	GitHub

**Data Preparation Steps**
1.	Extracted the ZIP dataset
2.	Loaded all four CSV files into pandas
3.	Merged datasets using:
o	pizza_id
o	pizza_type_id
o	order_id
4.	Created a revenue column (quantity × price)
5.	Converted date and time columns
6.	Created additional columns:
o	Hour
o	Day of week
o	Month

**Key Business Questions Answered**
•	What is the total revenue?
•	How many pizzas were sold?
•	How many total orders were placed?
•	How many pizza types are on the menu?
•	What is the average pizza price?
•	What are the peak sales hours?
•	Which day of the week generates the most sales?
•	What are the top 5 bestselling pizzas?
•	What are the monthly sales trends?
•	Which pizzas are underperforming?
Additional exploratory analysis was also performed beyond the required questions.

**Sample Insights **
•	Total revenue was approximately $817K
•	About 49K pizzas were sold across 21K orders
•	Peak sales hours occur during lunch and evening periods
•	Fridays and Saturdays generate the highest revenue
•	A small number of pizza types drive a large share of sales
•	Some specialty pizzas show consistently low demand

**Skills Demonstrated**
•	Multi-table joins in Pandas
•	Data cleaning and validation
•	Feature engineering from datetime data
•	Aggregation and grouping
•	Revenue calculations
•	Exploratory data analysis
•	Data visualization
•	Insight documentation
•	Business-focused reporting
•	Analytical storytelling

👤 Author
Musa Mamman
Data Analyst | Educator | SQL & Power BI Enthusiast
